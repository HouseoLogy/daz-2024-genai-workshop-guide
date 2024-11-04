# Understanding the Interface

The ComfyUI interface consists of several key areas that you'll use to build and execute your workflows.

![ComfyUI Interface Overview](/static/comfyui/intro/interface_overview.png)

## Key Interface Elements

### 1. Main Workspace (Grid Area)
- Dark grid background where you build your workflows
- Nodes can be placed and connected freely in this space
- Right-click to access the node menu

### 2. Nodes
- Building blocks of your workflow (e.g., 'Load Checkpoint', 'CLIP Text Encode', 'KSampler')
- Each node has:
  - Input connectors (left side)
  - Output connectors (right side)
  - Configurable parameters (shown within the node)

### 3. Right Panel
- Queue information (top)
- System resource usage
- Save/Load options
- Manager for extensions
- Image preview area

### 4. Workflow Controls
- Queue Prompt: Execute the current workflow
- Save: Save your current workflow
- Load: Load existing workflows
- Clear: Reset the workspace

> **💡 Quick Tips:**
- Double-click on the grid to quickly add new nodes
- Drag between node connectors to create links
- Right-click on connections to delete them
- View History for loading previous workflow executions

---

Next, we'll load our first simple workflow using these interface elements.