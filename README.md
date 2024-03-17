

![Screenshot 2024-03-17 011719](https://github.com/bumbeng/Fluidd_theme_simple/assets/111509593/addb324b-dfe0-45f0-be00-8b08f3a92515)

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
