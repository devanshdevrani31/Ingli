# Roadmap.md

## Overview
This roadmap outlines the development process for **Ingli**, a modern desktop app for data analysis using plain English commands. The project will leverage **Electron** for a sleek, cross-platform frontend and **Python** with **R** for backend data processing.

---

## Year-Long Roadmap

### **Phase 1: Planning and Foundation (Month 1-3)**

#### **Month 1: Project Setup (50 hours)**
- Finalize project scope and feature set.
- Set up GitHub repository with proper folder structure:
  - `src/`: Code files for frontend and backend.
  - `docs/`: Documentation files.
  - `tests/`: Test cases for backend and frontend.
- Choose tech stack:
  - **Frontend**: Electron + React + Tailwind CSS.
  - **Backend**: Python (`pandas`, `Flask`) + R (`ggplot2`).
- Deliverable: Repository setup and folder structure ready.

#### **Month 2: Architecture Design (40 hours)**
- Design the backend-frontend communication pipeline.
- Define data flow and command processing logic.
- Deliverable: Architecture document in `docs/`.

#### **Month 3: Initial Prototypes (40 hours)**
- Create a basic Electron app with a simple UI for command input.
- Connect the app to a mock backend.
- Deliverable: Basic Electron prototype.

---

### **Phase 2: Backend Development (Month 4-5)**

#### **Month 4: Build NLP and Backend Core (50 hours)**
- Implement NLP parser using OpenAI API or Hugging Face models.
- Define basic commands for filtering, grouping, and visualizing data.
- Develop API with Flask for handling frontend requests.
- Deliverable: Backend capable of handling basic commands.

#### **Month 5: Advanced Backend Features and Testing (50 hours)**
- Implement advanced data manipulation functions using `pandas`.
- Integrate Python with R for visualizations using `rpy2`.
- Write unit tests for backend modules.
- Deliverable: Fully functional backend with testing framework.

---

### **Phase 3: Frontend Development (Month 6-7)**

#### **Month 6: UI/UX Design and Initial Integration (50 hours)**
- Finalize UI designs in Figma.
- Build reusable React components for the Electron app.
- Connect Electron frontend to Flask backend via IPC or HTTP API.
- Deliverable: Basic frontend with backend integration.

#### **Month 7: State Management and Feature Completion (50 hours)**
- Add state management using Redux or Context API.
- Implement UI features like:
  - Command input box.
  - Dataset preview table.
  - Visualization display panel.
- Deliverable: Fully functional frontend connected to backend.

---

### **Phase 4: Visualization and Command Expansion (Month 8-9)**

#### **Month 8: Visualization Module (50 hours)**
- Add data visualization support using `matplotlib`, `seaborn` (Python) and `ggplot2` (R).
- Enable rendering of visualizations in the Electron frontend.
- Deliverable: Functional visualization module integrated with frontend.

#### **Month 9: Command Expansion and Session Management (50 hours)**
- Extend NLP to handle complex commands like "Group sales by region and plot totals."
- Add error handling for ambiguous commands.
- Implement saving and loading of user sessions.
- Deliverable: Enhanced command support and session management.

---

### **Phase 5: Testing and Optimization (Month 10-11)**

#### **Month 10: Comprehensive Testing (40 hours)**
- Perform integration tests for backend-frontend communication.
- Stress-test the app with large datasets.
- Deliverable: Fully tested and debugged app.

#### **Month 11: Optimization and Refinement (40 hours)**
- Optimize memory usage for handling large datasets.
- Refactor code for maintainability and performance.
- Deliverable: Optimized MVP ready for finalization.

---

### **Phase 6: Finalization (Month 12)**

#### **Month 12: Packaging and Documentation (50 hours)**
- Package the app for Windows, macOS, and Linux using Electron Builder.
- Finalize user and developer guides in the `docs/` folder.
- Create setup wizards for easy installation.
- Deliverable: Cross-platform app packages and complete documentation.

---

## Folder Structure
```
/ingli
├── README.md
├── LICENSE
├── docs/
│   ├── ROADMAP.md
│   ├── DESIGN.md
│   ├── PROCESS.md
│   ├── USER_GUIDE.md
│   ├── DEVELOPER_GUIDE.md
├── src/
│   ├── frontend/
│   └── backend/
├── tests/
├── assets/
```

---


