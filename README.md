🌐 Graph Builder - Interactive Network Visualization Tool
🎨 Create, visualize, and analyze interactive graphs with an intuitive drag-and-drop interface!

A powerful, browser-based tool for building and visualizing network graphs with advanced features including flow analysis, drawing tools, and dynamic interactions.
✨ Features
🎯 Core Functionality

🔴 Dynamic Node Creation - Add nodes with custom labels, colors, and sub-labels
🔗 Smart Link Management - Connect nodes with labeled relationships
🎨 Interactive Drawing Tool - Draw annotations directly on the graph
⚡ Flow Saturation Analysis - Analyze network flow equations automatically
🔍 Zoom & Pan Controls - Navigate large graphs with ease

🎪 Visual Elements

🌈 Color Customization - Choose from predefined palettes or custom colors
✨ Smooth Animations - Fluid node appearances and interactions
🎭 Modern UI Design - Glassmorphism effects and gradient backgrounds
📱 Responsive Layout - Works seamlessly on desktop and mobile

🛠️ Advanced Tools

✋ Move Mode - Drag and position nodes freely
✏️ Draw Mode - Sketch annotations with customizable brushes
🧽 Erase Mode - Remove drawings selectively
🎨 Color Palette - 8 predefined colors plus custom options
📏 Brush Size Control - Adjustable drawing thickness

🚀 Getting Started
📋 Prerequisites

Modern web browser (Chrome, Firefox, Safari, Edge)
No additional installations required!

🔧 Installation

Clone the repository
bashgit clone https://github.com/Edward03YT/Graph-Builder.git
cd graph-builder

Open in browser
bash# Simply open the HTML file in your browser
open grafuuu.html
# or
python -m http.server 8000  # For local server

Start building! 🎉

📖 Usage Guide
🎯 Creating Your First Graph

Add Nodes 🔴

Enter a unique ID (e.g., "A", "Start", "Node1")
Provide a display label
Optionally add a sub-label
Choose a color
Click "Adaugă Nod"


Connect Nodes 🔗

Select source and target nodes from dropdowns
Add an optional label (supports equations like "10 = 5+5")
Click "Adaugă Legătură"


Analyze Flow ⚡

Use equations in link labels (format: "result = calculation")
Click "Analizează Saturarea" to highlight:

🔴 Red links: Saturated (equations balance)
🔵 Blue links: Unsaturated (equations don't balance)





🎨 Drawing Tools
ToolIconFunctionMove✋Default mode - drag nodes aroundDraw✏️Sketch annotations on the graphErase🧽Remove drawn annotationsClear🗑️Remove all drawings
🎛️ Controls

🔍 Zoom: Mouse wheel or pinch gestures
📱 Pan: Click and drag empty space
🎯 Reset Zoom: Return to original view
📺 Fit Screen: Auto-fit all nodes in view
⚡ Force Strength: Adjust node repulsion (100-1000)

🏗️ Technical Architecture
🧩 Built With

HTML5 - Structure and layout
CSS3 - Modern styling with gradients and glassmorphism
Vanilla JavaScript - Core functionality and interactions
D3.js v7.8.5 - Force-directed graph visualization
Canvas API - Drawing functionality

📁 File Structure
graph-builder/
├── grafuuu.html          # Main application file
├── README.md            # This file
└── assets/              # (Optional) Additional resources
    ├── screenshots/     # Demo images
    └── examples/        # Sample graphs
🔧 Key Components
🎭 UI Sections

Sidebar: Control panel with all tools and settings
Main Canvas: Interactive graph visualization area
Drawing Layer: Canvas overlay for annotations
Controls: Zoom and simulation controls

⚙️ Core Functions
javascript// Node management
addNode()           // Create new nodes
removeNode(id)      // Delete nodes and connected links

// Link management  
addLink()           // Create connections between nodes
analyzeSaturation() // Perform flow analysis

// Drawing system
setDrawingMode()    // Switch between tools
clearDrawing()      // Reset canvas
🎨 Customization
🌈 Color Schemes
The application includes 8 predefined colors:

#667eea - Primary Blue
#764ba2 - Purple
#f093fb - Pink
#f5576c - Red
#4facfe - Light Blue
#00f2fe - Cyan
#43e97b - Green
#38f9d7 - Teal

🎛️ Physics Configuration
javascript// Force simulation parameters
.force("charge", d3.forceManyBody().strength(-400))    // Node repulsion
.force("link", d3.forceLink().distance(120))          // Link length
.force("collision", d3.forceCollide().radius(35))     // Collision detection
📊 Flow Analysis
The saturation analysis feature allows you to:

Define Equations in link labels using format: result = calculation

Example: 10 = 5+5 (saturated)
Example: 10 = 3+4 (unsaturated)


Visual Feedback:

🔴 Red thick lines: Saturated connections (equations balance)
🔵 Blue medium lines: Unsaturated connections (equations don't balance)
⚪ White thin lines: Regular connections (no equations)



🎯 Use Cases
📚 Educational

Network Theory: Visualize graph algorithms
Flow Networks: Analyze maximum flow problems
System Design: Model component relationships

💼 Professional

Process Modeling: Map business workflows
System Architecture: Design software systems
Data Flow: Visualize information pathways

🎨 Creative

Mind Mapping: Organize ideas visually
Storytelling: Create interactive narratives
Art Projects: Generate algorithmic art

🐛 Troubleshooting
Common Issues
ProblemSolutionNodes not appearingCheck console for JavaScript errorsLinks not connectingEnsure both nodes exist before creating linksDrawing not workingTry refreshing the page and switching modesPerformance issuesReduce number of nodes or adjust force strength
🔧 Browser Compatibility

✅ Chrome 80+
✅ Firefox 75+
✅ Safari 13+
✅ Edge 80+

🤝 Contributing
We welcome contributions! Here's how you can help:

🍴 Fork the repository
🌿 Create a feature branch (git checkout -b feature/AmazingFeature)
💾 Commit your changes (git commit -m 'Add some AmazingFeature')
📤 Push to the branch (git push origin feature/AmazingFeature)
🔄 Open a Pull Request

💡 Ideas for Contributions

📱 Mobile touch improvements
💾 Save/load graph functionality
🎨 Additional drawing tools
📊 Export to common formats (SVG, PNG, JSON)
🌍 Internationalization support

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
🙏 Acknowledgments

D3.js Community - For the amazing visualization library
MDN Web Docs - Comprehensive web development resources
Color Hunt - Inspiration for color palettes
Dribbble - UI/UX design inspiration

📞 Contact & Support

📧 Email: igame0303@gmail.com
🐛 Issues: GitHub Issues
💬 Discussions: GitHub Discussions


<div align="center">
⭐ If you found this project helpful, please give it a star! ⭐
Made with ❤️ by Edward
</div>