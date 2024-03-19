##### !! beta !!
# Feautures
- control slider
    - description is now above the    input field to prevent text wrapping
    - input field is now at full container width
- axis control buttons
    - are now in full container width, mobile and desktop browser (bars only)
- gcode viewer
    - division of input fields and buttons now 50% to avoid overlap
- transparent design
    - every background changes the entire look

choose your favourite background (rename to background.png)

# background
![Screenshot 2024-03-19 003104](https://github.com/bumbeng/Fluidd_theme_simple/assets/111509593/7f3f4082-56a8-412b-abad-753361065843)

# background_1
![Screenshot 2024-03-19 003258](https://github.com/bumbeng/Fluidd_theme_simple/assets/111509593/df21ea64-f8cf-4c5c-8dd9-d50d36233e29)

# background_2
![Screenshot 2024-03-19 003152](https://github.com/bumbeng/Fluidd_theme_simple/assets/111509593/bc32df70-2542-4605-a61f-2f92955fae39)



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
