# Domain-API-Caller-Chrome-Extension
Overview
The Domain API Caller Chrome Extension is a simple extension that allows you to quickly make API calls to a specific endpoint by adding the current webpage's domain as a query parameter. It simplifies the process of sending requests to a specific API endpoint without the need to manually copy and paste the domain.

Features
Automatically retrieves the current webpage's domain.
Appends the domain to a specified API endpoint as a query parameter.
Makes API calls with the updated URL for quick access to relevant data.
Installation
Clone this repository or download the source code as a ZIP file.

Open Google Chrome.

Chrome Icon

Go to chrome://extensions/.

Extensions

Enable "Developer mode" in the top right corner.

Developer Mode

Click on "Load unpacked" and select the folder where you saved the extension files.

Load Unpacked

The extension will be added to your Chrome browser.

Usage
Navigate to a webpage for which you want to make an API call.

Click on the Domain API Caller extension icon in the Chrome toolbar.

Extension Icon

The extension will automatically retrieve the domain of the current webpage and append it as a query parameter to the specified API endpoint.

You can now use the updated URL to make API calls directly to the relevant endpoint.

Configuration
You can configure the extension by editing the config.js file:

apiEndpoint: The base API endpoint to which the current domain will be appended.
queryParamName: The name of the query parameter used to pass the domain.
