# Open-Source-Project
Name: **Lavish Gupta** (11917631)

Sec: **KE023**

Roll No: **73**

## Topic : Use any open source software to potentially locate deleted emails and scan a disk for text strings to use them as a password dictionary to crack encryption.
### 1. Obtain a Disk Image of the Target System or Device:
The first step is to obtain a disk image of the target system or device. This can be done using various tools, such as FTK Imager or dd.

### 2. Install and Configure Bulk Extractor on a Forensic Workstation:
The next step is to install and configure Bulk Extractor on a forensic workstation. The tool can be downloaded from the official website, and the installation process is straightforward. Once installed, the tool can be configured by modifying the configuration file, which is located in the Bulk Extractor directory.

### 3. Extract Data from the Disk Image:
Once the tool is installed and configured, the next step is to extract data from the disk image. This can be done by running the following command in the command prompt:
```
bulk_extractor -o output_folder -R disk_image_file
```
This command will extract data from the disk image and store it in the specified output folder. The -R option tells Bulk Extractor to recursively search for data in the disk image.

### 4. Locate Potentially Deleted Emails:
To locate potentially deleted emails, use the following command:
```
bulk_extractor -o output_folder -R -E email disk_image_file
```
This command will extract all email addresses from the disk image, including those that may have been deleted. The -E option tells Bulk Extractor to extract only email addresses, and the output will be stored in the specified output folder.

### 5. Create a Wordlist for Password Cracking:
To create a wordlist for password cracking, use the following command:
```
bulk_extractor -o output_folder -R -e wordlist disk_image_file
```
This command will extract all words from the disk image and store them in a JSON file. This file can be used as a password dictionary for cracking encryption.

![i1](https://user-images.githubusercontent.com/62785215/230947844-88d04b54-cf3c-42ab-8a31-2dae80763195.png)
![i2](https://user-images.githubusercontent.com/62785215/230947895-eb67e9d2-dd3f-4b23-8be5-c1cbf1d53372.png)
![i3](https://user-images.githubusercontent.com/62785215/230947940-efe32ad3-dcaf-4d9d-a2fa-94e265a8e428.png)
![i4](https://user-images.githubusercontent.com/62785215/230947967-8b745a37-ce93-47af-8857-b6eddef09d2c.png)
![i5](https://user-images.githubusercontent.com/62785215/230948003-e91f1ed5-edc8-440b-a290-2f97477bbfea.png)
![i6](https://user-images.githubusercontent.com/62785215/230948050-8094bdd3-6f88-4109-b0a4-9a4db8f6beb2.png)
![i7](https://user-images.githubusercontent.com/62785215/230948084-abc8a2af-34a2-48d5-8342-8f771119cdf5.png)
