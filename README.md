
# Thymeleaf With Spring Boot AND CSS

## Using CSS With Thymeleaf Template
- You have option of using
  - Local CSS files as part of your project
  - Referencing remote CSS files

## CSS file location:
- Spring Boot will look for static resources in the directory
  - scr/main/resources/static

`Note: We can give any custom sub-directory name inside static direcory. Eg. css, css-files etc.`

## Other Search Directories:
- Spring Boot will search following directories for static resources under 'src/main/resources':
  - /META-INF/resources
  - /resources
  - /static
  - /public
  - 