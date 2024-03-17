##### !! beta !!
![Screenshot 2024-03-17 125628](https://github.com/bumbeng/Fluidd_theme_simple/assets/111509593/19003a09-509c-44d7-904b-bd3f4c7d319e)


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
