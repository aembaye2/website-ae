robocopy .\docs "Z:\public_html\" /E  /R:2 /W:2 

# if you want to send to github pages
robocopy .\docs "..\docs" /E  /R:2 /W:2 

