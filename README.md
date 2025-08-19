# Google Docs M3 Editor
This CSS theme aims to build on top of Google's overhaul of the Google Docs editor by adding another layer of customization.

> [!NOTE]
> This is a work-in-progress. Things are unfinished. Dark themes won't work well with this, and probably never will.

## What's changed?
There are numerous changes:
1. If you have the Circular STD font installed, that will become the new UI font. Circular STD will become the new font throughout the UI. It's clean and beautiful. However, it only works locally -- I can't host the font online due to licensing restrictions. However, you can [install the font and their weights]([url](https://font.gooova.com/fonts/14294/circular-std-font-family.html)) on your device and voilá! Otherwise, the UI will default to your system's default font.
2. There are more rounded corners for a friendlier look, including pages in Google Docs.
3. Colors are more emphasized, yet harmonized. You can also customize your color in accordance with Google's Material 3 UI guidelines.

## Where will this be applied?
1. Google Docs
2. Google Slides
3. Google Sheets
This theme was originally intended for Google Docs, so the theme may not be complete in other apps.

## Prerequisites
Use any CSS injector for your browser. CSS injectors allow you to inject custom CSS code into any website, including Google Docs. More instructions are written down under the Installation section.

# Showcases
Screenshots to preview if the theme fits your style!

## Color Screenshots
### Overview
There are 8 pre-made themes available:
![0818-ezgif com-crop (1)](https://github.com/user-attachments/assets/0c5d66ea-c804-4248-8dca-cb95350c1a1f)

### Themes
<img width="1536" height="870" alt="image" src="https://github.com/user-attachments/assets/6838947f-3e44-497c-8282-fb4dac132739" />

Red


<img width="1536" height="870" alt="image" src="https://github.com/user-attachments/assets/145713b7-369c-4731-9e2f-d29717f1a2d1" />

Orange


<img width="1536" height="870" alt="image" src="https://github.com/user-attachments/assets/637280c8-75e1-4cff-8d6b-9db5cdb74783" />

Yellow


<img width="1536" height="870" alt="image" src="https://github.com/user-attachments/assets/dcdc2d20-12b9-48fe-8933-bebac6ca6d0f" />

Green


<img width="1536" height="870" alt="image" src="https://github.com/user-attachments/assets/dd0a2b4a-9b72-4a10-9b39-c27c693100de" />

Turquoise/Aqua


<img width="1536" height="870" alt="image" src="https://github.com/user-attachments/assets/c78e467e-1a91-428b-8fe5-fc5c6b4b51c6" />

Blue


<img width="1536" height="870" alt="image" src="https://github.com/user-attachments/assets/10b8eb9a-1bd7-4aac-9a4a-c68537944407" />

Purple


<img width="1536" height="870" alt="image" src="https://github.com/user-attachments/assets/7e928168-a996-4673-8a2c-dd04fbe0b10d" />

Pink


**More themes are coming soon!** Alternatively, you can use the [Material Theme Builder]([url](https://material-foundation.github.io/material-theme-builder/)) to create your own colors and replace the color values in the `root {` element with the respective HEX codes that the generator gives you. Ensure you use the **light theme** values, **not the dark theme!**

<img width="919" height="641" alt="image" src="https://github.com/user-attachments/assets/d3badbeb-2d0f-4fb1-a3fe-5128452684b4" />

## Individual elements
The green theme is used as an example.

<img width="283" height="581" alt="image" src="https://github.com/user-attachments/assets/d3fdd4f3-8ed7-4326-8479-2bfebfb8cdab" />

### Outlines and tabs
The outlines and tabs sidebar is now a lot more round, while still easy and familiar to use. Your chosen accent color will take over the sidebar. You'll also notice the vertical bar is now rounded, and it helps keep things fit with the theme and much nicer to look at. It's also a pixel wider.

The font size for the header is now also larger.


<img width="337" height="398" alt="image" src="https://github.com/user-attachments/assets/50a13bf5-84cf-45fc-bb18-85975ea4c952" />

### Color picker
The color picker is now more rounded and in unison design-wise with other popups throughout Google Docs. Things are more friendly and fit the theme.

<img width="432" height="556" alt="image" src="https://github.com/user-attachments/assets/997a99c0-1166-490c-a06f-74095e81e57d" />

### Context menus
Context menus are also infused with your chosen color, as well as more rounded.

<img width="570" height="248" alt="image" src="https://github.com/user-attachments/assets/123cb4ad-3604-4d8d-9461-3b2b14e14ab8" />

### Pop-ups and message boxes
Are also tinted with your accent color, while looking more like Material 3.

<img width="360" height="227" alt="image" src="https://github.com/user-attachments/assets/07782275-b8cb-415e-b1ea-d765135ef851" />

### Comment editor
A simple, beautiful revamp of the comment editor that blends in seamlessly with the rest of the page.

<img width="237" height="81" alt="image" src="https://github.com/user-attachments/assets/d7d4b746-b085-4a86-ab6d-542791330c06" />

### Next tab indicator
Still a helpful and unobtrusive way to navigate to the next tab once you're done reading your current one.

<img width="863" height="458" alt="image" src="https://github.com/user-attachments/assets/ef74bcb5-357d-4d5a-aae1-ca91064a8635" />

### Rounded page corners
Without changing any page settings or layouts, pages now look more like it's part of Material 3 and are more user-friendly and inviting.


# Installation
"Installation" is easy! In fact, you don't need to install anything at all -- it's simply a CSS script you have to copy and paste into a CSS injector.

## 1. Find a CSS Injector
For Chrome, you can find CSS Injectors on the Chrome Web Store. I personally use [this one]([url](https://chromewebstore.google.com/detail/css-inject/ieplmpooeagjhcgcpoapbonpfmekpkic?hl=en)). With the Chrome Store cracking down on these sorts of things, some well-built injectors have sadly been removed. However, any CSS Injector will do. There also may be extensions for different browsers, such as Firefox or Safari that allow you to do this as well.

## 2. Set the domain
Most injectors will automatically set the domain (the website your style will apply to) if you visit the website (in this case, Google Docs) and then open the injector. For others, you may have to manually set it yourself. For more information, refer to your injector's description or instructions for specifics.

## 3. Paste the main code
Go to `M3-Docs-Main.css` in this repository and copy the raw CSS code to your clipboard. Then, paste it in the script editor of your injector.

## 4. Change the color scheme
Unless you're happy with the default, you can change the color to a preset theme (or a custom one, with a guide on this coming soon). Simply choose any color inside of the "Themes" folder in this repository, copy its code (in which the only class in the file would be `:root {`), then replace the color values of the main script in your injector's script editor with the ones you just pasted.

## 5. Keep your theme somewhere safe
Most injectors automatically save your things, but clearing your browser's storage or cache will delete the theme. Copy everything inside your script's editor once you're satisfied with theming, then paste it into somewhere safe, like a Google Doc or a .css file of your own. This also allows you to share your theme with others!
