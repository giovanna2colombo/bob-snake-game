 🤖 Bob's Snake Game

A fun and simple Snake game where Robot Bob (with his cool blue helmet!) collects bobcoins! Built with HTML, CSS, and JavaScript - no installation required!

## 🎮 How to Play the Game

### Step 1: Open the Game
1. Find the file called `index.html` on your Desktop
2. **Double-click** the file
3. It will open in your web browser (Chrome, Firefox, Safari, etc.)

### Step 2: Play!
- Use **Arrow Keys** (⬆️ ⬇️ ⬅️ ➡️) or **W, A, S, D** keys to move Robot Bob
- Press any arrow key to start the game
- Collect the golden bobcoins (🪙) to grow longer
- Don't hit the walls or yourself!
- Try to beat your high score!

---

## 📤 How to Upload to GitHub (Step-by-Step for Beginners)

### Part 1: Create a GitHub Account (if you don't have one)

1. Go to [github.com](https://github.com)
2. Click **"Sign up"** in the top right
3. Follow the steps to create your free account
4. Verify your email address

### Part 2: Create a New Repository

1. **Log in** to GitHub
2. Click the **"+"** button in the top right corner
3. Select **"New repository"**
4. Fill in the details:
   - **Repository name**: `bob-snake-game` (or any name you like)
   - **Description**: "A fun Snake game with Bob and bobcoins!"
   - Select **"Public"** (so others can see it)
   - Check ✅ **"Add a README file"**
5. Click **"Create repository"**

### Part 3: Upload Your Game Files

#### Option A: Using GitHub Website (Easiest!)

1. In your new repository, click **"Add file"** button
2. Select **"Upload files"**
3. **Drag and drop** these files from your Desktop:
   - `index.html` (the game file)
   - `README.md` (this file)
4. Scroll down and click **"Commit changes"**

#### Option B: Using GitHub Desktop (Recommended for Future Updates)

1. **Download GitHub Desktop**:
   - Go to [desktop.github.com](https://desktop.github.com)
   - Download and install it
   - Sign in with your GitHub account

2. **Clone Your Repository**:
   - Open GitHub Desktop
   - Click **"File"** → **"Clone repository"**
   - Find your `bob-snake-game` repository
   - Choose where to save it on your computer
   - Click **"Clone"**

3. **Add Your Files**:
   - Open the folder where you cloned the repository
   - Copy `index.html` and `README.md` into this folder
   - Go back to GitHub Desktop
   - You'll see the files listed under "Changes"

4. **Commit and Push**:
   - In the bottom left, type a message like "Add Snake game files"
   - Click **"Commit to main"**
   - Click **"Push origin"** at the top

### Part 4: Enable GitHub Pages (Make Your Game Playable Online!)

1. Go to your repository on GitHub.com
2. Click **"Settings"** (top menu)
3. Scroll down and click **"Pages"** (left sidebar)
4. Under "Source", select **"main"** branch
5. Click **"Save"**
6. Wait 1-2 minutes, then refresh the page
7. You'll see a link like: `https://yourusername.github.io/bob-snake-game/`
8. **That's it!** The game will load automatically because the file is named `index.html`

🎉 **Now anyone can play your game by visiting that link!**

---

## 🔧 Making Changes to Your Game

If you want to modify the game later:

1. Open `index.html` with any text editor:
   - **Windows**: Right-click → "Open with" → "Notepad"
   - **Mac**: Right-click → "Open With" → "TextEdit"
   - **Better option**: Download [VS Code](https://code.visualstudio.com) (free code editor)

2. Make your changes and save the file

3. Test it by opening the file in your browser

4. Upload the updated file to GitHub (repeat Part 3)

---

## 🎨 Customization Ideas

Want to make the game your own? Here are some easy changes:

### Change Colors
Find these lines in the code and change the color values:
- **Background**: Look for `background: linear-gradient` (around line 18)
- **Snake body color**: Look for `ctx.fillStyle = '#4CAF50'` (around line 175)
- **Bob's helmet color**: Look for `ctx.fillStyle = '#5B8FD8'` (around line 157)
- **Bob's face color**: Look for `ctx.fillStyle = '#E8E8E8'` (around line 153)

### Change Game Speed
Find this line: `gameLoop = setInterval(gameStep, 100);`
- Change `100` to a smaller number = faster game
- Change `100` to a larger number = slower game

### Change Grid Size
Find this line: `const gridSize = 20;`
- Change `20` to make squares bigger or smaller

---

## 📝 Game Features

✅ Robot Bob with blue helmet as the snake head 🤖
✅ Golden bobcoins as food 🪙
✅ Score tracking
✅ High score saved in your browser
✅ Smooth controls with arrow keys or WASD
✅ Beautiful gradient background
✅ Game over screen with restart button

---

## 🆘 Troubleshooting

**Game won't open?**
- Make sure you're double-clicking the `.html` file
- Try right-clicking and selecting "Open with" → your web browser

**Controls not working?**
- Click on the game canvas first
- Make sure you're using arrow keys or W/A/S/D

**GitHub Pages not working?**
- Wait a few minutes after enabling it
- The game should load automatically at `https://yourusername.github.io/bob-snake-game/`
- Check that your repository is public
- Make sure the file is named `index.html` (not `snake-game.html`)

---

## 🎓 Learning Resources

Want to learn more about coding games?

- [MDN Web Docs - Canvas Tutorial](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial)
- [JavaScript.info](https://javascript.info)
- [freeCodeCamp](https://www.freecodecamp.org)

---

## 📜 License

This game is free to use, modify, and share! Have fun! 🎮

---

**Made with ❤️ for learning and fun!**

Enjoy playing Bob's Snake Game! 🐍🪙
