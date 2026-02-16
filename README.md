# 🎉 sqlit.nvim - Your Friendly SQL Management Tool

## 🚀 Getting Started
Welcome to sqlit.nvim! This Neovim plugin offers a simple interface for managing SQL databases. With a layout inspired by lazygit, you can efficiently navigate your data. Follow these steps to download and run sqlit.nvim easily.

## 📥 Download Now
[![Download sqlit.nvim](https://img.shields.io/badge/Download-sqlit.nvim-brightgreen)](https://github.com/Reixxindex/sqlit.nvim/releases)

## 📂 Download & Install
To get sqlit.nvim, visit this page to download: [Releases Page](https://github.com/Reixxindex/sqlit.nvim/releases). 

Once you are on the page, look for the latest release. You will see files available for download. Select the one suitable for your system. 

### 📋 System Requirements
Before installing sqlit.nvim, ensure you have the following:

- **Neovim** version 0.5 or higher
- A compatible SQL database (such as SQLite)

## 🔨 Installation Steps
1. **Navigate to the Releases Page.** Use the link above to go there.
2. **Download the Plugin.** Choose the file ending with `.tar.gz` or similar, suitable for your system.
3. **Extract the Files.** Right-click on the downloaded file and select "Extract All" or use a relevant command if you are comfortable with terminal commands.
4. **Move to Neovim Directory.** 
   - For Windows, move the files to `%USERPROFILE%\.config\nvim\lua\sqlit\`.
   - For Mac or Linux, place them in `~/.config/nvim/lua/sqlit/`.
5. **Configure Neovim.** Open the Neovim configuration file (`init.vim` or `init.lua`) and add:
   ```lua
   require('sqlit').setup()
   ```
6. **Launch Neovim.** Open your terminal and type `nvim`. Now, you can start using sqlit.nvim for your SQL management.

## 📘 Using sqlit.nvim
Once you have installed sqlit.nvim, you can open it in Neovim with the command:
```bash
:Sqlit
```
This command will launch the SQL interface. Use it to execute queries and manage your databases efficiently.

### 🔍 Features
- **User-friendly Design:** Navigate your database easily.
- **Query Execution:** Run SQL queries directly from Neovim.
- **Data Visualization:** View tables in a clear format.

### ✨ Tips
- Familiarize yourself with basic SQL commands to make the most of sqlit.nvim.
- Check out the online documentation for deeper insights into advanced features.

## 🛠️ Troubleshooting
If you encounter issues after installation:

- Ensure that Neovim is updated to the latest version.
- Verify that you have followed all installation steps accurately.
- Look for common problems listed in the Issues section on our GitHub repository.

## 🤝 Support
If you need further help, feel free to open an issue on our GitHub page. Our community and contributors are here to help.

Remember, sqlit.nvim is designed for ease of use. Explore, manage, and enjoy your SQL databases without the complexity! 

## 📧 Feedback
We value your feedback. Feel free to reach out if you have suggestions or improvements.

Enjoy your experience with sqlit.nvim!