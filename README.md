# RevoU Week 3 Assignment

## Site Features

- **Header Section:** Displays the title "PIKUNIKKU" and subtitle "STICKER CATALOGUE" with a sticky position to keep it visible at the top of the page as you scroll.
- **About Section:** Provides brief information about Pikunikku, including location, commission status, and available products.
- **Catalogue Section:** Shows different sticker sheets and keyrings with images and descriptions. **If you hover on each image, the image will scale up, showing you the availability. For now, the out-of-stock one is the Monthly Journalling Sticker Sheet. So if you hover on it, the image will turn grayscale, and there's an "Out-of-stock" info.**
- **Contact Section:** Allows visitors to send messages via a simple contact form.
- **Responsive Design:** The website has been designed to be more responsive, providing an optimal viewing experience on smaller devices.

## Additional Information

- Google font used in this project is Winkle.
- Image section are made using Asymmetrical Grid.
- Media query are optimized for 1440px, with small adjustment at 1024px and 550px.
- Text shadow are applied to some texts to make it more clear.

## Sign-up to Netlify

1. Go to netlify.com

2. Click 'Log-in'

3. Log-in with GitHub

## Deploying on Netlify from GitHub

1. Go to 'Sites', click 'Import from Git' in the 'Import an existing project' section

<div style="text-indent: 30px;">
    <img src="./Screenshots/Part 2 - SS 1A.jpeg" width="100" style="max-width:100%; height:auto;">
    <img src="./Screenshots/Part 2 - SS 1B.jpeg" width="400" style="max-width:100%; height:auto;">
</div>

2. Deploy your project from GitHub

<div style="text-indent: 30px;">
    <img src="./Screenshots/Part 2 - SS 2.jpeg" width="400" style="max-width:100%; height:auto;">
</div>

3. A pop-up window will appear for authorization. Click 'Authorize Netlify' and wait for the authorization process to complete

<div style="text-indent: 30px;">
    <img src="./Screenshots/Part 2 - SS 3.jpeg" width="400" style="max-width:100%; height:auto;">
</div>

4. Choose the account where you want to install the site on Netlify

<div style="text-indent: 30px;">
    <img src="./Screenshots/Part 2 - SS 4A.jpeg" width="400" style="max-width:100%; height:auto;"><br>
</div>
<div style="text-indent: 30px;">
    <img src="./Screenshots/Part 2 - SS 4B.jpeg" width="400" style="max-width:100%; height:auto;"><br>
</div>
<div style="text-indent: 30px;">
    <img src="./Screenshots/Part 2 - SS 4C.jpeg" width="400" style="max-width:100%; height:auto;">
</div>

5. Select the repository. Initially, I used my classroom account but switched to my personal account later on. Unfortunately, I forgot to capture screenshots during this transition to my new account. So ere's the previous screenshot that I took with my classroom account

<div style="text-indent: 30px;">
    <img src="./Screenshots/Part 2 - SS 5.jpeg" width="400" style="max-width:100%; height:auto;">
</div>

6. Enter the site name, scroll down, and click 'Deploy (your site name)'

<div style="text-indent: 30px;">
    <img src="./Screenshots/Part 2 - SS 6A.jpeg" width="400" style="max-width:100%; height:auto;"><br>
</div>
<div style="text-indent: 30px;">
    <img src="./Screenshots/Part 2 - SS 6B.jpeg" width="400" style="max-width:100%; height:auto;"><br>
</div>
<div style="text-indent: 30px;">
    <img src="./Screenshots/Part 2 - SS 6C.jpeg" width="400" style="max-width:100%; height:auto;">
</div>

## Auto Deploy

Once you deploy the site, it will be automatically deployed when you push somethings to your GitHub repository.

<div style="text-indent: 30px;">
    <img src="./Screenshots/Part 3 - SS 1.jpeg" width="400" style="max-width:100%; height:auto;">
</div>

## Buying a Domain from Niagahoster

1. Log in to Niagahoster

2. Search for the desired domain name

<div style="text-indent: 30px;">
    <img src="./Screenshots/Part 4 - SS 2A.jpeg" width="400" style="max-width:100%; height:auto;"><br>
</div>
<div style="text-indent: 30px;">
    <img src="./Screenshots/Part 4 - SS 2B.jpeg" width="400" style="max-width:100%; height:auto;">
</div>

3. Choose the domain from the list. For example, I selected hellopikunikku.site

<div style="text-indent: 30px;">
    <img src="./Screenshots/Part 4 - SS 3.jpeg" width="400" style="max-width:100%; height:auto;">
</div>

4. Click 'Beli domain'

<div style="text-indent: 30px;">
    <img src="./Screenshots/Part 4 - SS 4.jpeg" width="400" style="max-width:100%; height:auto;">
</div>

5. Complete the payment process

<div style="text-indent: 30px;">
    <img src="./Screenshots/Part 4 - SS 5A.jpeg" width="400" style="max-width:100%; height:auto;"><br>
</div>
<div style="text-indent: 30px;">
    <img src="./Screenshots/Part 4 - SS 5B.jpeg" width="400" style="max-width:100%; height:auto;"><br>
</div>
<div style="text-indent: 30px;">
    <img src="./Screenshots/Part 4 - SS 5C.jpeg" width="400" style="max-width:100%; height:auto;">
</div>

6. Fill out the registration form

<div style="text-indent: 30px;">
    <img src="./Screenshots/Part 4 - SS 6.jpeg" width="400" style="max-width:100%; height:auto;">
</div>

7. Done! The domain has been purchased

<div style="text-indent: 30px;">
    <img src="./Screenshots/Part 4 - SS 7A.jpeg" width="400" style="max-width:100%; height:auto;"><br>
</div>
<div style="text-indent: 30px;">
    <img src="./Screenshots/Part 4 - SS 7B.jpeg" width="400" style="max-width:100%; height:auto;">
</div>

## Setting DNS

1. Go to 'Domain management' in your Netlify account and add your custom domain name

<div style="text-indent: 30px;">
    <img src="./Screenshots/Part 5 - SS 1.jpeg" width="400" style="max-width:100%; height:auto;">
</div>

2. Click 'Add domain'

<div style="text-indent: 30px;">
    <img src="./Screenshots/Part 5 - SS 2.jpeg" width="400" style="max-width:100%; height:auto;">
</div>

3. After successfully adding your custom domain to Netlify, you can find the necessary DNS information as follows: Netlify typically provides this information in the form of an A record. You might see details like "Fallback Point A record to 75.2.60.5". This A record contains the specific numerical values you need to configure in your domain registrar (Niagahoster) under the 'DNS/Nameserver' settings

<div style="text-indent: 30px;">
    <img src="./Screenshots/Part 5 - SS 3A.jpeg" width="400" style="max-width:100%; height:auto;"><br>
</div>
<div style="text-indent: 30px;">
    <img src="./Screenshots/Part 5 - SS 3B.jpeg" width="400" style="max-width:100%; height:auto;">
</div>

4. In Niagahoster, navigate to 'DNS/Nameserver' and add the number obtained from the previous step

<div style="text-indent: 30px;">
    <img src="./Screenshots/Part 5 - SS 4.jpeg" width="400" style="max-width:100%; height:auto;">
</div>

5. Confirm the addition of the A record

<div style="text-indent: 30px;">
    <img src="./Screenshots/Part 5 - SS 5.jpeg" width="400" style="max-width:100%; height:auto;">
</div>

6. Delete the previous A record from the list in Niagahoster

<div style="text-indent: 30px;">
    <img src="./Screenshots/Part 5 - SS 6.jpeg" width="400" style="max-width:100%; height:auto;">
</div>

7. Back in Netlify, click on the 'Options' button next to your custom domain information, and select 'Set up Netlify DNS'

<div style="text-indent: 30px;">
    <img src="./Screenshots/Part 5 - SS 7.jpeg" width="400" style="max-width:100%; height:auto;">
</div>

8. Wait for the process to complete. You can refresh the page after a while. The setup is complete when a checklist icon with 'Netlify DNS' text appears next to your custom domain information

<div style="text-indent: 30px;">
    <img src="./Screenshots/Part 5 - SS 8.jpeg" width="400" style="max-width:100%; height:auto;">
</div>
