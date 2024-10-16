# Setup Instructions

## 1. Install JetBrains Tools
Download the JetBrains Toolbox from the official website:  
[JetBrains Toolbox](https://www.jetbrains.com/lp/toolbox/)

---

## 2. Extract and Install Required Dependencies
- Extract the downloaded `.tar.gz` file.
- Navigate to the extracted folder.  
  Inside, locate the `jetbrains-toolbox` file.
  
- Open a terminal in the same directory and run the following command to install the required dependency:

  ```bash
  sudo apt-get install -y libfuse2

## 3. Run jetbrains-toolbox
- wait for few minutes, tool box will pop up.
- Install IntelliJ Idea community edition
## 5. Install Postman from App Center
## 6. Install curl
- Run the following commands to update your system and install `curl`:
 ```bash
 sudo apt update
 ```
 ```bash
 sudo apt install curl
 ```
## 7. Install Postman from App Center (Ubantu System app)
![Logo](https://www.ezone.co.uk/images/badges/256/app-center-t.png)

## 8. Open Terminal and Install SDKMAN

- SDKMAN helps manage multiple SDKs. Run the following commands to install SDKMAN:
```bash
curl -s "https://get.sdkman.io" | bash
```
```bash
source "$HOME/.sdkman/bin/sdkman-init.sh"
```
```bash
sdk version
```
## 9. List Available Java Versions
- Use the following command to list available Java versions:
```bash
sdk list java
```
- Example output:
```bash
 Vendor        | Use | Version      | Dist    | Status     | Identifier
 GraalVM CE    |     | 23           | graalce |            | 23-graalce          
               |     | 22.0.2       | graalce |            | 22.0.2-graalce      
               |     | 21.0.2       | graalce |            | 21.0.2-graalce      
               |     | 17.0.9       | graalce |            | 17.0.9-graalce 
```
## 10. Install a Specific Java Version
- To install a Java version using its identifier, run:
- Generic: sdk install java `<Identifier>`

```bash
sdk install java 17.0.9-graalce
```
- This will also set Java 17 as the default version.


