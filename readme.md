# **ChakriyaJaiya Photography Portfolio Website**

This is a simple photography portfolio website for showcasing beautiful images. The site features a dynamic image slider on the home page and a gallery page to display the full collection.

## **Project Overview**

- **Homepage**:
  - Contains a large dynamic image slider that changes images every 5 seconds.
  - Includes a "View Gallery" button that links to the gallery page.
  
- **Gallery Page**:
  - Displays a collection of photos in a grid layout.

## **Technologies Used**

- **ASP.NET Core Razor Pages**: For server-side web application development.
- **HTML/CSS**: For the structure and styling of the website.
- **JavaScript**: For the dynamic image slider functionality.

## **Project Structure**

```
ChakriyaJaiya/
│
├── wwwroot/
│   ├── css/
│   │   └── site.css               # Main stylesheet for the website
│   └── images/                    # Folder for storing images
│       ├── CKYJY_Sample1.png
│       ├── CKYJY_Sample2.png
│       └── CKYJY_Sample3.png
│
├── Pages/
│   ├── Index.cshtml               # Home page with image slider
│   ├── Gallery.cshtml             # Gallery page for displaying photos
│   ├── About.cshtml               # (Future) About page
│   ├── Contact.cshtml             # (Future) Contact page
│   └── Shop.cshtml                # (Future) Shop page for selling photos
│
├── Program.cs                     # ASP.NET Core entry point and middleware configuration
├── appsettings.json               # Configuration settings
└── README.md                      # Project overview and instructions
```

## **Getting Started**

Follow these steps to get the project up and running on your local machine.

### **1. Prerequisites**

- [.NET SDK](https://dotnet.microsoft.com/download) installed on your machine.
- A code editor, like [Visual Studio Code](https://code.visualstudio.com/).

### **2. Clone the Repository**

Clone this repository to your local machine using:

```bash
git clone https://github.com/your-username/ChakriyaJaiya.git
cd ChakriyaJaiya
```

### **3. Running the Application**

1. Open the project in your code editor.
2. Use the terminal to run the following command:

```bash
dotnet run
```

3. Open your web browser and navigate to `http://localhost:5244` (or the port specified in your terminal) to see the website in action.

## **File Details**

- **Index.cshtml**:
  - This is the home page of the website.
  - Contains an image slider that switches between three photos every 5 seconds.
  - Includes a link to the gallery page (`/Gallery`).

- **site.css**:
  - The main stylesheet for the website.
  - Styles the home page, image slider, and other components.
  - Ensures responsiveness and basic layout design.

- **JavaScript in Index.cshtml**:
  - Controls the image slider functionality, automatically transitioning images every 5 seconds.
  - Adjust the slider interval by changing the `setTimeout` duration in the script section.

## **To-Do List**

- [ ] Improve slider transitions (add smoother animations or different effects).
- [ ] Add more pages (e.g., About, Contact).
- [ ] Implement an e-commerce section for selling photos.
- [ ] Optimize images for faster loading.
- [ ] Make the website mobile-friendly.

## **Known Issues**

- **Image Slider Not Loading**: Ensure all images are correctly placed in the `wwwroot/images` directory and referenced properly in `Index.cshtml`.

## **Contributing**

If you want to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## **License**

This project is open-source and available under the MIT License.

## **Contact**

If you have any questions, feel free to reach out at [your-email@example.com](mailto:your-email@example.com).
```

### How to Use This

1. **Create a New File**:
   - In your project directory, create a new file named **`README.md`**.

2. **Paste the Markdown Content**:
   - Copy the content above and paste it into your new **`README.md`** file.

3. **Save the File**:
   - Save the file. Your project now has a `README.md` that clearly explains what your project is about, how to set it up, and how to contribute.

This `README.md` will be displayed automatically on platforms like GitHub, GitLab, or Bitbucket when someone visits your repository, making it easier to share your progress and collaborate with others.