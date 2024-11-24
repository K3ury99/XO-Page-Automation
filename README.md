# 🚀 XO-Page-Automation
> [!IMPORTANT]
The automated project is called "Tarea_4.py.". Use this small code to run the program from the CMD
```text
   pytest Tarea_4.py --html=report.html
   ```

<div style="display: flex;">
  <img src="https://github.com/K3ury99/XO-Page-Automation/blob/main/imagenes/login_fallido.png" width="49%"></img> 
  <img src="https://github.com/K3ury99/XO-Page-Automation/blob/main/imagenes/login_con_credenciales_2.png" width="49%"></img>   
</div>
<div style="display: flex;">
  <img src="https://github.com/K3ury99/XO-Page-Automation/blob/main/imagenes/pagina_formulario.png" width="49%"></img> 
  <img src="https://github.com/K3ury99/XO-Page-Automation/blob/main/imagenes/inicio_scroll.png" width="49%"></img>   
</div>

> [!TIP]
This is the page I used in this automation project, I also uploaded the folder in this repository and it's hosted on Netlify.
```text
   https://bondelic.netlify.app/
   ```

# 🛠️ **Project Features**
1. **Automated Tests:**
   - Empty login (no credentials).
   - Login with valid credentials.
   - Scroll to the bottom of the homepage.
   - Navigation to the products page.
   - Navigation to the registration form page.

2. **Screenshots:**
   - Captures images at key points during each test, storing them in the `imagenes` folder.

3. **Browser Configuration:**
   - Uses **Microsoft Edge** with a maximized window for optimal visibility during tests.

4. **Acceptance and Rejection Criteria:**
   - Each test is validated with clear and well-documented criteria to ensure system quality.

markdown
Copiar código
📂 Project Structure

# 📦 Selenium Project  
 ┣ 📂 images  
 ┃ ┗ 📄 (Contains the screenshots generated by the tests)  
 ┣ 📄 test_script.py  (Main file with automated tests)  
 ┣ 📄 README.md        (This file)  
 ┗ 📄 requirements.txt (Project dependencies)  

## 🐱‍👤 Contributing
1. **Fork the repo**
- **Create a new branch**
   ```bash
   git checkout -b feature-branch
- **Commit changes**
   ```bash
  git commit -am 'Add new feature'
2. **Push to the branch (git push origin feature-branch)**
3. **Create a new Pull Request**

# 📋 **Prerequisites**
Before running this project, make sure you have the following components installed:
- **Python 3.0**
- **Selenium WebDriver**
- **Microsoft Edge WebDriver**
- Required libraries (install them with `pip install selenium pytest`).

## 📔 License
This project is licensed under the MIT License. See the LICENSE file for details.
