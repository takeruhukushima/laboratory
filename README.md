# my lab page

This is the my lab page source code.
This was created based on Agora's landing page.
I plan to change the design as I believe it may be considered rude.
The design will continue to change based on my mood going forward.
If there is a license violation, please let me know.

# Development Notes

## Docker
# Build the image
docker build -t lablatory-app .
# Run the container
docker run -d --name lablatory-container -p 8080:80 lablatory-app
# Start the container
docker start lablatory-container
# Stop the container
docker stop lablatory-container
# Remove the container
docker rm lablatory-container

## License

This work is based on [AppLight](https://www.free-css.com/free-css-templates/page295/applight), a template from W3Template.com.

This is source-available, but not open-source software. 

Refer to [License.txt](./License.txt) for details.

