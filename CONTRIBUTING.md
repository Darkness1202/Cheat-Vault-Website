# Contributing to CheatVault

Thank you for your interest in contributing to CheatVault! 🎮

## How to Contribute

### Adding New Games

1. Fork the repository
2. Open `index.html` in your favorite code editor
3. Find the `gamesDatabase` array in the `<script>` section
4. Add your game entry following this format:

```javascript
{
    title: "Game Title",
    platform: "PC", // Options: PC, PlayStation, Xbox, Nintendo
    year: "2024",
    category: "Modern", // Options: Modern (2010+) or Classic (before 2010)
    cheats: [
        {
            name: "Cheat Name",
            code: "actual_cheat_code_here",
            description: "Clear description of what this cheat does"
        },
        // Add more cheats...
    ]
}
```

### Guidelines

#### Game Selection
- Focus on popular, well-known games
- Include games from various eras (1990s to present)
- Cover multiple platforms and genres

#### Cheat Code Quality
- ✅ **DO**: Provide accurate, tested cheat codes
- ✅ **DO**: Include clear descriptions
- ✅ **DO**: Specify if cheats require special setup (console commands, save editors, etc.)
- ❌ **DON'T**: Include cheats that require paid software
- ❌ **DON'T**: Include online multiplayer cheats/hacks
- ❌ **DON'T**: Include cheats that violate terms of service

#### Code Style
- Maintain consistent formatting
- Use clear, descriptive names
- Keep descriptions concise but informative
- Test your additions in a browser before submitting

### Submission Process

1. **Fork** the repository
2. **Create a branch** for your changes
   ```bash
   git checkout -b add-new-games
   ```
3. **Make your changes** to `index.html`
4. **Test locally** by opening the file in a browser
5. **Commit** your changes
   ```bash
   git commit -m "Add [Game Name] with X cheats"
   ```
6. **Push** to your fork
   ```bash
   git push origin add-new-games
   ```
7. **Create a Pull Request** with a clear description

### Pull Request Guidelines

- **Title**: Clear and descriptive (e.g., "Add Halo Infinite with 8 cheats")
- **Description**: 
  - List games added
  - Number of cheats per game
  - Any special notes or considerations
- **Testing**: Confirm you've tested the page loads correctly

### Reporting Issues

Found a bug or incorrect cheat code?

1. Go to the [Issues](../../issues) page
2. Click "New Issue"
3. Provide:
   - Clear title
   - Detailed description
   - Steps to reproduce (if applicable)
   - Expected vs actual behavior

### Code of Conduct

- Be respectful and constructive
- Focus on educational/entertainment value
- No malicious code or exploits
- Credit sources when appropriate

## Questions?

Feel free to open an issue for any questions about contributing!

---

**Happy Gaming! 🎮**
