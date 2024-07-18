# Cartoonify_an_Image

Cartoonify an Image Using OpenCV [Python]

- Cartoonifying an image using OpenCV involves transforming a photograph into a cartoon-like image by applying various image processing techniques. 
- The process begins by converting the image to grayscale to facilitate edge detection. A median blur is applied to reduce noise, followed by edge detection to highlight the edges. 
- The edges are then enhanced through binary thresholding. Simultaneously, the original image undergoes bilateral filtering to smooth the colors while preserving edges, creating a simplified and stylized appearance.
- Finally, the edge mask is combined with the smoothed color image to produce a cartoon-like effect, resulting in a visually appealing, cartoonified version of the original photograph.

INPUT:
- Input Image(Girl.jpg)

OUTPUT:
- GrayScale Image
- Edged Image
- Binary Edged Image
- Quantized Image
- Blurred Quantized Image
- Cartoon Image
