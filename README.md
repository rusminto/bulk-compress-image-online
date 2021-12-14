# bulk-compress-image-online
It's tool to compress bulk of images with bash script and TinyPNG

To use this tool, you have to create account at https://tinify.com/ and get API Key

To run this tool, you have to :
1. ensure file "compressImage" is executable
2. create path to "compressImage", like insert ```export PATH="/Users/user/Documents/bulk-compress-image-online:$PATH"``` at ~/.bashrc or ~/.zshrc
3. ensure that export is success by run ```source ~/.zshrc``` or ```source ~/.bashrc```
4. finally, run "compressImage" on another directory that consist of images
5. compressed image can be found at directory output/
