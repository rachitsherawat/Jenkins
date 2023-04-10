
# Installing Jenkins on ubuntu

jenkins installation commands 




## ERROR

Package jenkins is not available, but is referred to by another package.This may mean that the package is missing, has been obsoleted, oris only available from another source

## Installation

Install my-project with npm

```bash
  •	curl -fsSL https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key | sudo tee \
/usr/share/keyrings/jenkins-keyring.asc > /dev/null

```
```bash
 •	echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] \
https://pkg.jenkins.io/debian-stable binary/ | sudo tee \
/etc/apt/sources.list.d/jenkins.list > /dev/null

```
```bash
•	sudo apt-get update
```
    ```bash
•	sudo apt-get install jenkins
```
## Acknowledgements

 - [jenkins site ](https://www.jenkins.io/doc/book/installing/linux/#debianubuntu)

