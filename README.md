## 🚀 Quick Start
1. Download `SudokuDemo.jar`
2. Run: `java -jar SudokuDemo.jar`
3. Load puzzles from `PUZZLES.zip` folder
4. 
![Sudoku Demo Interface](https://github.com/Sudokoach/Artificial-Sudoku-Player/blob/071f61bf6944c80142309346cdc9147165fe636c/Sudoku%20Demo%20Interface.png)

# 🧩 Sudoku Reasoning Demo - GUI Description

## 🎯 **Interactive Sudoku Solver Interface**

### **Main Grid Display**
- **9×9 Sudoku grid** with pencil marks and solved cells
- **Color-coded cells**:
  - **Yellow**: Solved cells
  - **Cyan**: Pencil marks (candidate numbers)
  - **Red**: Excluded candidates
- **Multi-digit displays** show all possible candidates in each cell

### **Reasoning Information Panel**

#### **Difficulty Grades**
- **Grade 1-4**: Progressive difficulty indicators
- **Next Step**: Current solving technique being applied

#### **Solving Technique Display**
- **XY-S-Wing**: Advanced Sudoku technique identified
- Shows the specific logical pattern used

#### **Exclusion Graph Visualization**
```
[373, 354, 454, 456, 447, 437, 337] -> Excluded: 373
```
- **Chain of reasoning**: Node-to-node exclusion path
- **Closed loop**: Starts and ends proving candidate exclusion
- **Visual proof**: Demonstrates why candidate must be excluded

#### **Node Features Analysis**
```
[2,4,3,3] [2,4,3,3] [2,2,2,2] [3,2,2,2] [2,2,2,2] [2,2,2,2] [2,3,3,2]
```
- **Feature vectors** for each node in the reasoning chain
- **Format**: `[k, r, c, b]` - candidate frequencies in cell, row, column, block
- **Quantitative analysis** of constraint relationships

## 🔍 **Key Features Demonstrated**
1. **Visual Reasoning**: See exactly why each elimination occurs
2. **Step-by-Step Logic**: Follow the chain of deductions
3. **AI-Powered Insights**: Transformer model identifies complex patterns
4. **Educational Value**: Learn advanced Sudoku techniques
5. **Real-time Feedback**: Immediate visual confirmation of logic

## 🚀 **User Experience**
- **Intuitive interface** for both beginners and experts
- **Learning tool** for understanding Sudoku logic
- **Research demonstration** of AI reasoning capabilities
- **Interactive exploration** of solving strategies

This demo bridges the gap between **human intuition** and **AI-powered logical reasoning**! 🧠✨
