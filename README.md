##### !! beta !!

choose your favourite background (rename to background.png)

# background
![Screenshot 2024-03-17 191728](https://github.com/bumbeng/Fluidd_theme_simple/assets/111509593/ecb37df9-c108-4b03-ae93-597efc0aaf2e)

# background_1
![Screenshot 2024-03-17 191252](https://github.com/bumbeng/Fluidd_theme_simple/assets/111509593/d5119026-6831-4e4c-a582-e03009fe05bc)

# background_2
![Screenshot 2024-03-17 191337](https://github.com/bumbeng/Fluidd_theme_simple/assets/111509593/00be0212-a29a-4155-96bd-412b6a017bb2)



## How to install
- make hidden folders visible
- create a folder called .fluidd-theme in config section
- copy the downloaded files into this folder
- reload browser

## Logo change
- name an picture to logo.png
- put this image to .fluidd-theme
- insert these lines with `!! your url !!` of the logo.png file into custom.css

      .logo-wrapper[data-v-7fe7065f] {
      
            display: none;
          }
          .theme--dark .toolbar-logo[data-v-b360135f] {
              background-image: url(http://mainsailos.local/server/files/config/.fluidd-theme/logo.png)!important;
              background-size: cover!important;
      }
