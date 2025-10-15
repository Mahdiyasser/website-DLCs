## Accessing Your Website Add-On

Once an add-on is integrated into your website, there are two primary ways for users to access it:

### 1. Linking Method (Recommended for Users)
The most common and user-friendly method is to create a visible element on your website that links to the add-on's URL. This could be:
* A dedicated **button**
* A **navigation link**
* A visual **card**
* Any other linking method you prefer

### 2. Direct URL Entry (For Testing or Direct Use)
Users can also access the add-on by typing its **full, specific URL** directly into their browser's address bar.

**Example:**
If the add-on is a "dashboard," the URL might look like:
`https://yourdomain.com/dashboard`

---

## Hosting Your Website Add-Ons

For the add-ons to function correctly, they need to be served by a web server.

### 1. Traditional Web Servers
If you are self-hosting your website, you must serve the add-on files using a web server like **Apache2** or **Nginx**.

### 2. Standard Hosting Providers
If you use a **commercial hosting provider**, simply uploading the add-on's folder to your site's directory (e.g., via FTP or a file manager) is typically all that is required. The provider's existing web server infrastructure will handle the rest.

### 3. GitHub Pages
Most add-ons will work successfully when hosted on **GitHub Pages**, *unless* the add-on requires a **backend server** or server-side processing to function. Static front-end add-ons are generally fine.
