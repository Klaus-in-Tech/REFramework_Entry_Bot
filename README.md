# Entry using UiPath REFramework

### Process Flow
![entrybot drawio](https://github.com/Klaus-in-Tech/REFramework_Entry_Bot/assets/31986394/2eb61c44-294e-480a-b675-882749b8e34c)

This project aims to automate the process of entering data into the rpachallenge website using UiPath with the REFramework

### Features

1. **Open the rpa chalenge website**: https://rpachallenge.com/

2. **Enter the 20 rows of data into the website**

3. **Error Handling**: Implement robust error handling to deal with exceptions, ensuring the process runs smoothly.

4. **Logging**: Enable detailed logging to track the status and actions performed during the automation.

### Pre-requisites

Before you run the automation, make sure you have the following installed on your PC:

- UiPath Studio.
- Excel.
- Chrome Browser.

### Installation and Usage

1. Clone or download the repository to your local machine.

2. Open the UiPath Studio and load the "Main.xaml" workflow.

3. Update the configuration file ("Config.xlsx") in the Data folder with the necessary details.
   
4. Save the changes and execute the workflow.

### How It Works

1. The automation will read the configuration from the "Config.xlsx" file.

2. It will open https://rpachallenge.com/

3. It will read the input file

4. For each data row in the input file, it will enter the data into the rpa challenge website.

5. Updates the processed column with YES, No - Business exception and No - System exception.

### Note

- This automation is for educational purposes and may require modifications to suit your specific use case.
 
### License

This project is licensed under the MIT License. For more details, please see the `LICENSE` file.

### Contact

If you have any questions or need assistance, you can reach me via `kakoozaallanklaus@outlook.com`.

## Author
- [Github](https://github.com/Klaus-in-Tech)
- [LinkedIn](https://www.linkedin.com/in/kakoozaallanklaus/)
- [Twitter](https://twitter.com/Klaus_in_Tech)

### Feel free to connect with me on my social media, as listed above. 😊
