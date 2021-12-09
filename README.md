# MultiPHP

## Installation

- Clone this repo: ```git clone https://github.com/isaeken/multiphp.git```
- Move repo to secure folder example: ``C:\dev\multiphp``
- Install dependencies: ```composer install --no-dev --optimize-autoloader```
- Add path to environment variables
- Run ```multiphp``` command in your terminal and enter binary directory & environment directory
  - Example binary directory: ```C:\dev\bin```
  - Example environment directory: ```C:\dev\php```
- Download & configure php versions (7.3, 7.4, 8.0, 8.1) to environment directory
  - Example: ```C:\dev\php\8.1\php.exe```

### Change PHP environment

Open terminal and run 
```bash
multiphp change version=8.1
```