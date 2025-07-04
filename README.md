# React component library

This project is a reusable React component library built with Create React App and Storybook. 
All components are styled with Styled Components, fully responsive, and include Storybook controls for easy property editing.

---

# Getting Started

# Option 1: Running with Docker (Recommended)

# Prerequisites

- Docker installed on your machine.

# Clone the repository

```sh
git clone <REPO_URL>
cd lopez_laura_ui_garden
```

# Build the Docker image

```sh
docker build -t laura_lopez_coding_assignment12 .
```

# Run the Docker container


```sh
docker run --rm -p 8083:8083 --name laura_lopez_coding_assignment12 laura_lopez_coding_assignment12
```

**Note:** The container will show nginx logs and appear to "hang" - this is normal! It's running successfully.

# Open Storybook

Visit [http://localhost:8083] in your browser to view the component library.

# Stop the container

**Press `Ctrl+C` in the terminal**

## Container Details

- **Image name:** `laura_lopez_coding_assignment12`
- **Container name:** `laura_lopez_coding_assignment12`
- **Working directory:** `/laura_lopez_ui_garden`
- **Port:** `8083`