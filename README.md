# proof-delete-flag-admin-theme

A custom theme which deletes flags of admin theme in Liferay 7.1.

## How I did it?
1. I created a theme with the [generator](https://portal.liferay.dev/docs/7-1/tutorials/-/knowledge_base/t/creating-themes) of Liferay
2. I changed the *src* folder for the *src* folder of the [admin-theme](https://github.com/liferay/liferay-portal/tree/7.1.x/modules/apps/frontend-theme/frontend-theme-admin) (Ensure that in the *liferay-look-and-feel.xml* mark the theme as an admin theme.
3. I deployed the theme in my instance and selected it as the admin theme in *Control Panel -> Configuration -> Instance Settings -> Miscellaneous*.
4. I made the changes to hide the flags.
