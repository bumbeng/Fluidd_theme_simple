##### !! beta !!
![Screenshot 2024-03-17 053934](https://github.com/bumbeng/Fluidd_theme_simple/assets/111509593/a243dc9b-4bf6-4e6e-8d97-a2be34cb128c)

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
