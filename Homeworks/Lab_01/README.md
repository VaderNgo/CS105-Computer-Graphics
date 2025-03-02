
# Computer Graphics Rasterization Tool

![Rasterization Tool Banner](https://github.com/user-attachments/assets/cf4cb82e-f910-4136-9d6c-71e93edd0224)

## Overview

This project implements fundamental rasterization algorithms for computer graphics, providing an interactive web-based tool for visualizing line drawing and circle generation techniques. It offers a hands-on approach to understanding the core concepts of pixel-based rendering through direct manipulation and real-time visualization.

## Features

- **Multiple Rasterization Algorithms**:
  - **Line Drawing**: DDA (Digital Differential Analyzer) and Bresenham's algorithm
  - **Circle Drawing**: Mid-Point Circle algorithm
  
- **Interactive Interface**:
  - Intuitive point selection for defining lines
  - Adjustable radius control for circles with real-time preview
  - Clean canvas reset functionality
  
- **Visual Guidance**:
  - Step-by-step instructions for each drawing operation
  - Helpful tips for optimal usage
  
- **Responsive Design**:
  - Fully functional across devices of different screen sizes
  - Adaptive layout for both desktop and mobile viewing

## Technical Implementation

### Core Algorithms

The tool implements three fundamental rasterization algorithms:

1. **DDA Algorithm**: Calculates intermediate points along a line using floating-point arithmetic, demonstrating a straightforward approach to line rasterization.

2. **Bresenham's Line Algorithm**: Employs integer-only arithmetic to efficiently determine pixel positions along a line, avoiding floating-point calculations for improved performance.

3. **Mid-Point Circle Algorithm**: Uses the mid-point approach to determine which pixels to illuminate when drawing a circle, balancing accuracy and computational efficiency.

### User Interface

The interface was designed with emphasis on:

- **Clarity**: Clear visual feedback during the drawing process
- **Accessibility**: Intuitive controls with minimal learning curve
- **Education**: Integrated guidelines that explain the drawing process

## Getting Started

### Prerequisites

- Modern web browser (Chrome, Firefox, Safari, or Edge)
- No additional installations required

### Running the Application

1. Clone the repository:
   ```
   git clone https://github.com/VaderNgo/CS105-Computer-Graphics.git
   ```

2. Navigate to the project directory:
   ```
   cd CS105-Computer-Graphics/Homeworks/Lab_01
   ```

3. Open `index.html` in your web browser

### Usage Instructions

#### Drawing a Line:
1. Select a line algorithm (DDA or Bresenham)
2. Click on the canvas to set the starting point (Point A)
3. Click again to set the ending point (Point B)
4. The line will be rendered automatically using the selected algorithm

#### Drawing a Circle:
1. Select the Mid-Point Circle algorithm
2. Use the slider or +/- buttons to set the desired radius
3. Click on the canvas to place the center of the circle
4. The circle will be rendered automatically with the specified radius

## Learning Outcomes

This tool helps demonstrate:

- How continuous mathematical forms (lines, circles) are approximated in discrete pixel spaces
- The trade-offs between different rasterization approaches
- The importance of efficiency in graphics algorithms
- How user interaction can be integrated with rendering algorithms

## Project Structure

```
.
├── index.html              # Main HTML file with UI structure
├── src/
│   ├── main.js             # Core application logic
│   ├── dda.js              # DDA line algorithm implementation
│   ├── bresenham.js        # Bresenham line algorithm implementation
│   └── midpoint.js         # Mid-point circle algorithm implementation
│   └── basic.js            # Set pixel on canvas
└── README.md               # Project documentation
```

## Future Enhancements

- Add support for additional shapes (ellipses, rectangles)
- Implement anti-aliasing techniques
- Add color selection for different elements
- Include algorithm performance metrics
- Add animation to visualize algorithm execution

## Course Information

- **Course**: CS105 - Computer Graphics
- **Institution**: University of Information Technology - Vietnam National University (UIT-VNU)
- **Student**: Ngo Duc Loc
- **Student ID**: 22520790
