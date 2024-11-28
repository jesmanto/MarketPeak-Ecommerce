# MarketPeak ECommerce
This platform will feature product listing, a shopping cart and user authentication.

## Step 1 - Implement Version Control with Git
### 1.1. Initialize Git Repository
- Open the terminal on your local machine.
- Navigate to your preferred location.
- Create a directory named "MarketPeak_Ecommerce" by using the command `mkdir MarketPeak_Ecommerce`.
- Navigate into the new directory by using `cd MarketPeak_Ecommerce`.
- Inside the new director, call the git command `git init` to initialize git in the directory.

    ![](./img/git_init.png)

- You should see a `.git` file when you ls into the directory using `ls -la`

    ![](./img/verify_git.png)

### 1.2. Obtain and Prepare the E-commerce Website Template
Rather than building a wesite from scratch, you can use pre-built debsite templates, and focus on the operational and deployment aspects. You can get these templates for free online. Let's get started.
- Download the [Waso Strategy HTML Template
](https://www.tooplate.com/view/2130-waso-strategy) from tooplate wesite.
    - On the page, scroll down a little, you'll find the download button.
    - Click on the download button and select the destination folder.
    ![](./img/download.png)
- Extract the downloaded template into your project directory, _**MarketPeak_Ecommerce**_. In my case, I used a linux comman to do that.

    `unzip -d ./  ~/downloads/2130_waso_strategy.zip`

### 1.3. Stage and Commit the Template to Git
- Add you project files to your local repository staging area. `git .`
