# Custom Graphics for Site Visuals, Buttons, Backgrounds, and More

This guide describes how to upload and use custom graphics in the Og-agent-web project. Whether you are sourcing graphics from Canva or other platforms, follow these steps to enhance your site's visuals.

## Step 1: Sourcing Graphics

1. **Create or find your visuals**: Use tools like [Canva](https://www.canva.com/) to create custom graphics, or download graphics from other websites.
2. **Ensure proper formats**: Common formats include PNG, JPEG, and SVG. PNG is preferred for graphics with transparent backgrounds.

## Step 2: Uploading Graphics

1. **Access the `public/assets/` directory** within your project.
2. **Upload your graphic files** to the `public/assets/` directory. This can usually be done via your file system or directly in the code repository interface (like GitHub).

## Step 3: Using Custom Graphics

### For Site Visuals and Buttons

1. In your HTML files, reference the uploaded graphics using the path to the `public/assets/` directory:
   ```html
   <img src="/public/assets/your-image-file.png" alt="Description of image">
   ```

### For Backgrounds

1. To set a custom background image in your CSS, use:
   ```css
   body {
       background-image: url('/public/assets/your-background-image.png');
       background-size: cover;
       background-repeat: no-repeat;
   }
   ```

## Step 4: Testing

1. After uploading and linking your graphics, **test your site** to ensure that the graphics are loading correctly and displaying as intended.
2. Make adjustments to sizes and positions as necessary to fit your site’s design.

## Conclusion

Using custom graphics can significantly enhance the visual appeal of your site. Follow the above steps, and feel free to reach out for support if you encounter any issues!