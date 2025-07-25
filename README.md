# Path Vision - Pathfinding Algorithm Visualizer

A interactive web-based pathfinding algorithm visualizer built with React that demonstrates how various pathfinding algorithms work in real-time. Perfect for learning computer science algorithms and understanding their behavior visually.

## 🌟 Features

### Pathfinding algorithms
- **Dijkstra's Algorithm** - Guarantees shortest path, explores uniformly
- **A* (A-Star)** - Heuristic-based, faster than Dijkstra for single target
- **Breadth-First Search (BFS)** - Guarantees shortest path for unweighted graphs
- **Depth-First Search (DFS)** - Explores deeply, doesn't guarantee shortest path

### Interactive Features
- **Interactive Grid** - Click and drag to draw walls
- **Real-time Visualization** - Watch algorithms explore the grid step by step
- **Maze Generation** - Generate random mazes to test algorithms
- **Speed Control** - Adjust animation speed (Fast, Medium, Slow)
- **Responsive Design** - Automatically adjusts for mobile devices
- **Clear Visualization** - Distinct colors for visited nodes, walls, and shortest path

### User Interface
- Clean, intuitive navigation bar
- Algorithm selection dropdown
- Speed control options
- Reset and clear functionality
- Responsive grid that adapts to screen size

## 🚀 Installation

### Prerequisites
- [Node.js](https://nodejs.org/) (v14 or higher recommended)
- [npm](https://www.npmjs.com/) (comes with Node.js)

### Setup Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/Raj-Jai/path-vision.git
   cd path-vision
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

### Build for Production
```bash
npm run build
```

### Deploy to GitHub Pages
```bash
npm run deploy
```

## 🎮 How to Use

### Basic Usage
1. **Select an Algorithm** - Choose from Dijkstra, A*, BFS, or DFS
2. **Draw Walls** - Click and drag on the grid to create obstacles
3. **Generate Maze** - Use the maze generator for complex patterns
4. **Adjust Speed** - Choose visualization speed that suits your preference
5. **Visualize** - Click the visualize button to see the algorithm in action
6. **Reset** - Clear the grid to try different configurations

### Understanding the Visualization
- **Green Node** - Start position (top-left)
- **Red Node** - End position (bottom-right)  
- **Black Nodes** - Walls/Obstacles
- **Light Blue Nodes** - Visited by algorithm
- **Yellow Path** - Shortest path found

## 🏗️ Project Structure

```
path-vision/
├── public/                 # Static assets
├── src/
│   ├── algorithms/         # Pathfinding algorithm implementations
│   │   ├── dijkstra.js    # Dijkstra's algorithm
│   │   ├── astar.js       # A* algorithm  
│   │   ├── bfs.js         # Breadth-First Search
│   │   ├── dfs.js         # Depth-First Search
│   │   └── mazeGenerator.js # Maze generation logic
│   ├── components/         # React components
│   │   ├── Navbar.jsx     # Navigation bar
│   │   ├── Grid.jsx       # Main grid component
│   │   ├── Node.jsx       # Individual grid node
│   │   └── Footer.jsx     # Footer component
│   ├── App.jsx            # Main application component
│   ├── index.js           # Application entry point
│   └── index.css          # Global styles
├── package.json           # Dependencies and scripts
└── README.md             # Project documentation
```

## 🛠️ Technologies Used

- **React** (v19.1.0) - Frontend framework
- **Styled Components** (v6.1.18) - CSS-in-JS styling
- **React Router DOM** (v7.6.2) - Navigation
- **Lucide React** (v0.513.0) - Icons
- **GitHub Pages** - Deployment platform

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 Future Enhancements

- Add more pathfinding algorithms (Greedy Best-First Search, Jump Point Search)
- Implement weighted nodes with different traversal costs
- Add diagonal movement options
- Include algorithm complexity analysis
- Save and load grid configurations

## 🐛 Troubleshooting

### Common Issues

**"Module not found" errors:**
```bash
rm -rf node_modules package-lock.json
npm install
```

**Build fails:**
```bash
npm run build
```
Check for any syntax errors in the code.

**Slow performance:**
- Try reducing grid size on older devices
- Use faster animation speed settings


## 👨‍💻 Author

**Jai Raj** - [GitHub Profile](https://github.com/Raj-Jai)

## 🙏 Acknowledgments

- Inspired by classical pathfinding algorithms in computer science
- Built as an educational tool for algorithm visualization
- Thanks to the React community for excellent documentation

---

**Live Demo:** [https://raj-jai.github.io/path-vision](https://raj-jai.github.io/path-vision)

Happy pathfinding! 🗺️✨
