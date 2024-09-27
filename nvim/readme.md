
# Neovim Installation and Usage Guide

### Installing Neovim on Ubuntu

1. **Update the system**:
   ```bash
   sudo apt update
   sudo apt upgrade
   ```

2. **Install Neovim**:
   ```bash
   sudo apt install neovim
   ```

3. **Check installation**:
   ```bash
   nvim --version
   ```

4. **Configure Neovim (Optional)**:
   Configuration file: `~/.config/nvim/init.vim`

   Example settings:
   ```vim
   set number
   set relativenumber
   set tabstop=4
   set expandtab
   ```

5. **Install Plugin Manager (Optional)**:
   ```bash
   curl -fLo ~/.local/share/nvim/site/autoload/plug.vim --create-dirs \
   https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
   ```

---

### Common Command Using Neovim

1. **Open the program**:
   ```bash
   nvim
   ```

2. **Modes**:
   - **Normal Mode**: Press `i` to enter **Insert Mode**
   - **Insert Mode**: Press `Esc` to return to **Normal Mode**
   - **Visual Mode**: Press `v`
   - **Command Mode**: Press `:`

3. **Basic Commands**:
   - Save the file: `:w`
   - Exit the program: `:q`
   - Save and exit: `:wq`
   - Force quit without saving: `:q!`

4. **Opening files**:
   ```bash
   nvim filename.txt
   ```

5. **Searching and replacing text**:
   - Search: `/text_to_search`
   - Replace: `:%s/text_to_search/text_to_replace/g`

6. **Installing plugins**:
   - Open `init.vim` and add:
     ```vim
     call plug#begin('~/.vim/plugged')
     Plug 'preservim/nerdtree'
     call plug#end()
     ```
   - Install plugins with:
     ```vim
     :PlugInstall
     ```

---