## SuperShop - Single Vendor Ecommerce Application


### FrontEnd Application Folder Structure

```
├───app
│   ├───Http
│   │   └───Controllers
│   └───Models
├───config
├───public
│   ├───assets
│   │   ├───css
│   │   ├───fonts
│   │   ├───images
│   │   └───js
│   └───uploads
│       ├───admins
│       ├───banners
│       ├───products
│       └───slides
└───resource
    ├───files
    └───view
        ├───content
        └───include
```


## Folder Structure Description

### `app/`
The main application logic is found here.

- **`Http/Controllers/`**: This folder contains the controllers that handle HTTP requests and responses.
- **`Models/`**: Contains Eloquent models that manage data relationships and database structure.

### `config/`
Holds configuration files for the application. These files contain settings for various services such as databases, mail, and third-party APIs.

### `public/`
This folder holds all public-facing files accessible by the user.

- **`assets/`**: Contains static assets like CSS, JavaScript, images, and fonts.
  - **`css/`**: Holds all the cascading stylesheets used in the application.
  - **`fonts/`**: Fonts used in the user interface.
  - **`images/`**: Images used in the front-end of the application.
  - **`js/`**: JavaScript files for adding interactivity to the user interface.
  
- **`uploads/`**: Stores files uploaded by users or administrators.
  - **`admins/`**: Files uploaded by admin users.
  - **`banners/`**: Contains banner images or media.
  - **`products/`**: Contains product images and related files.
  - **`slides/`**: Media files for slideshows or carousels.

### `resource/`
This folder contains the application's views and additional resources.

- **`files/`**: Stores miscellaneous static files used in the application.
- **`view/`**: Blade templates for rendering front-end pages.
  - **`content/`**: Contains the main content pages.
  - **`include/`**: Holds reusable partials like headers, footers, and other common sections.

## How to Use This Structure

1. **Controllers**: Develop and manage the logic for handling incoming requests and returning responses inside `app/Http/Controllers/`.

2. **Models**: Create or modify Eloquent models that define your database structure and relationships in `app/Models/`.

3. **Static Assets**: Place styles, fonts, images, and JavaScript files in the appropriate folders under `public/assets/` to manage front-end assets.

4. **Uploads**: Manage any user-uploaded files in the `public/uploads/` directory. Organize uploads into the appropriate subfolders (`admins`, `banners`, `products`, `slides`).

5. **Views**: Customize the front-end of the application by editing the Blade templates located in `resource/view/`. Add reusable components like headers and footers in `resource/view/include/`.

- Invoice Generate
- User Registration
- User Login
- User Dashboard
