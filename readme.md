# Resource Allocation Graph Simulator

The **Resource Allocation Graph Simulator** is a web-based tool designed to simulate and analyze resource allocation graphs (RAGs). It allows users to model processes and resources, add edges to represent requests or allocations, and check for potential deadlocks in the system.

## Features

- **Interactive Graph Visualization**: Create and visualize processes and resources as nodes, and their relationships as edges.
- **Deadlock Detection**: Analyze the graph to detect potential deadlocks.
- **Action History**: View and manage a history of actions performed on the graph.
- **Undo/Redo Functionality**: Easily revert or reapply changes.
- **Graph Export/Import**: Save the current graph state to a file or load a previously saved graph.
- **Dark Mode**: Toggle between light and dark themes for better visibility.
- **Graph Summary**: View a summary of the graph, including the number of processes, resources, and edges.

## How to Use

1. **Add Nodes and Edges**:
   - Enter a process (e.g., `P1`) and a resource (e.g., `R1`) in the input fields.
   - Select the type of edge:
     - `Request (P → R)`: Represents a process requesting a resource.
     - `Allocate (R → P)`: Represents a resource allocated to a process.
   - Click **Add Edge** to add the edge to the graph.

2. **Check for Deadlocks**:
   - Click **Check Deadlock** to analyze the graph for potential deadlocks.
   - The status will display whether a deadlock is detected or not.

3. **Manage Graph**:
   - **Export Graph**: Save the current graph as a JSON file.
   - **Import Graph**: Load a graph from a JSON file.
   - **Remove Selected**: Delete selected nodes or edges from the graph.
   - **Undo/Redo**: Revert or reapply the last action.
   - **Save History**: Download the action history as a text file.

4. **Customize View**:
   - Use the **Dark Mode** toggle to switch between light and dark themes.

5. **View Action History**:
   - The **Action History** panel displays a log of all actions performed.
   - Filter actions by type (e.g., `Add Edge`, `Remove`, `Import`, `Export`).
   - Clear the history if needed.

6. **Graph Summary**:
   - The **Graph Summary** panel shows the number of processes, resources, and edges in the graph.

## Technical Details

- **Frontend**: Built using HTML, CSS, and JavaScript.
- **Graph Library**: Utilizes the [vis-network](https://visjs.github.io/vis-network/) library for graph visualization.
- **Responsive Design**: The layout is optimized for various screen sizes.
- **Animations**: Smooth transitions and animations for better user experience.

## File Structure

- **HTML**: The main structure and logic for the simulator.
- **CSS**: Styling for the simulator, including light and dark themes.
- **JavaScript**: Handles graph operations, deadlock detection, and user interactions.

## Contributors

- Raman Kumar
- Bhavishya Verma
- Yogesh

## License

This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).

## Screenshots

### Light Mode
![Light Mode Screenshot](#)

### Dark Mode
![Dark Mode Screenshot](#)

## Future Enhancements

- Add support for advanced deadlock detection algorithms.
- Provide detailed reports for detected deadlocks.
- Enable real-time collaboration for multiple users.

## Feedback

If you encounter any issues or have suggestions for improvement, feel free to reach out or create an issue in the repository.