# Green-and-Dark-HA-Theme
A dark theme with green accents for Home Assistant based off green_dark_mode by JuanMTech, with mods by dmyoung9

##Enable themes in Home Assistant

Create a themes directory in your Home Assistant Config directory

Add this to your configuration.yaml

frontend:
  themes: !include_dir_merge_named themes
### Sample Picture

![firefox_oC3qer9YuA](https://user-images.githubusercontent.com/6832191/162251678-bfee2954-2aba-4f92-a05b-285134917bf4.png)

### HACS

1. Go to the Community Store.
2. Search for `Green and Dark Theme`.
3. Navigate to `Green and Dark Theme` theme.
4. Press `Install`.
5. Go to services and trigger the `frontend.reload_themes` service.

### Manual Install
Copy yaml file to your Home Assitant directory \config\themes\
  
