### What is Linux OS?

Linux is a free, open-source operating system known for its security, flexibility, and stability. It is widely used on servers, desktops, and mobile devices.

### Basic Linux Commands

- **pwd**: Prints the current working directory.
- **ls**: Lists files and directories.
- **cd**: Changes the directory.
- **mkdir**: Creates a directory.
- **touch**: Creates a file.
- **cat**: Prints the content of a file.
- **id**: Prints user and group IDs.

### Linux File System

All files and directories in Linux are organized under the root directory (/), which forms the base of the entire file system hierarchy.

### How to Install Linux OS (Any Distribution)?

1. **Bare Metal**: Install Linux OS directly on the hardware.
2. **Virtualization**: Install Linux OS on a virtual machine using tools like VirtualBox or Hyper-V.
3. **Cloud**: Install Linux OS on the cloud using providers like AWS, Azure, or GCP.
4. **Container**: Install Linux OS on containers using tools like Docker or Kubernetes.

### Hosting Apache HTTPD Web Server on Redhat Linux OS

- Use the below command to install Apache web server on Linux OS:
```
sudo yum install -y httpd
```

- Use the below Command to edit the index.html file:
```
sudo vi /var/www/html/index.html
```

- Use the below command to start the Apache web server:
```
sudo systemctl start httpd
```

- Use the below command to stop the Apache web server:
```
sudo systemctl stop httpd
```

### vi editor

- Use the below command to edit the file using vi editor:
```
vi <file-name>
```

- Use the below command to insert the text in the file:
```
i
```

- Use the below command to save the file:
```
:wq
```

- Use the below command to exit from the file without saving the file:
```
:q!
```
