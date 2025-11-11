# Bellman-Ford vs Dijkstra Algorithm Visualizer

An interactive web application that visualizes and compares two popular shortest path algorithms side-by-side.

## 🎯 Features

- **Side-by-Side Comparison** - Watch both algorithms solve the same graph simultaneously
- **Step-by-Step Visualization** - Control execution speed or step through manually
- **Real-Time Distance Tracking** - See shortest distances update as algorithms progress
- **Negative Weight Handling** - Demonstrates why Dijkstra fails with negative edges
- **Interactive Controls** - Run, Pause, Step, and Reset buttons for full control

## 🚀 Demo

Visit the live demo at the given link

## 📊 Algorithm Comparison

| Feature | Bellman-Ford | Dijkstra |
|---------|--------------|----------|
| **Negative Weights** | ✅ Supported | ❌ Not supported |
| **Negative Cycle Detection** | ✅ Yes | ❌ No |
| **Time Complexity** | O(V·E) | O((V+E)log V) |
| **Approach** | Relaxes all edges V-1 times | Greedy: picks closest node |

## 📝 How to Use

1. Click **"Run Both"** to watch both algorithms execute simultaneously
2. Use **"Step"** to advance one iteration at a time
3. Click **"Reset"** to start over
4. Observe how Bellman-Ford handles the negative edge (C→B: -3) while Dijkstra detects the error

## 📄 License

MIT License - Feel free to use and modify!

## 🤝 Contributing

Issues and pull requests are welcome!

---
