# HounaarToolkit

<img src="https://github.com/hounaar/HounaarToolkit/blob/main/logo.png">

HounaarToolkit is a versatile Python toolkit that provides a set of tools for various tasks, including data analysis, YouTube video downloading, cryptocurrency price checking, typing automation, network scanning, and rootkit detection. This toolkit aims to simplify and streamline these common tasks into a single, easy-to-use package.



## Features

- **Data Analysis AI:** Perform data analysis with AI-powered tools to gain insights from your data effortlessly.

- **YouTube Downloader:** Download YouTube videos and playlists with ease, all from the command line.

- **Cryptocurrency Price Checker:** Get real-time cryptocurrency prices and information for your favorite coins.

- **Type Rover:** Automate typing tasks by simulating keyboard input. Useful for repetitive typing jobs.

- **Network Scanner:** Scan your network to discover connected devices and check their status.

- **Rootkit Scanner:** Detect rootkits and suspicious system files to ensure the security of your system.

## Installation

You can install HounaarToolkit using pip or git cloning

```bash
git clone https://github.com/hounaar/HounaarToolkit.git
```

However, for installing via pip you need to do some steps first.
First, make sure you have Python 3.x installed on your system.

```bash
pip install HounaarToolkit
```

After installation, you'll need to add the HounaarToolkit executable to your system's PATH. Here's how you can do it on different platforms:

### Windows

1. Find the directory where HounaarToolkit was installed. Typically, it's located here:

   ```
   C:\Users\YourUsername\AppData\Roaming\Python\Python{YourPythonVersion}\Scripts
   ```

2. Copy the path to this directory.

3. Open the Start menu, search for "Environment Variables," and select "Edit the system environment variables."

4. In the System Properties window, click the "Environment Variables" button.

5. In the Environment Variables window, under "System Variables," find the "Path" variable, select it, and click the "Edit" button.

6. In the Edit Environment Variable window, click the "New" button, and paste the path to the HounaarToolkit directory.

7. Click "OK" to save your changes.

### Linux and macOS

1. Open a terminal window.

2. Run the following command, replacing `/path/to/HounaarToolkit` with the actual path to the HounaarToolkit executable directory:

   ```bash
   export PATH=$PATH:/path/to/HounaarToolkit
   ```

   You can also add this command to your shell's configuration file (e.g., `~/.bashrc` or `~/.zshrc`) to make it permanent.

Now you can run HounaarToolkit from any terminal window by simply typing `hounaartoolkit`.

## Usage

Once HounaarToolkit is added to your PATH, you can run it from the command line:

```bash
hounaartoolkit
```

Choose from the following commands:

1. Data Analysis AI
2. YouTube Downloader
3. Cryptocurrency Price Checker
4. Type Rover
5. Network Scanner
6. Rootkit Scanner
7. Exit

Select the tool you want to use by entering the corresponding number.

## Requirements

HounaarToolkit requires the following Python libraries, which will be automatically installed when you install the package using pip:

- numpy
- pandas
- matplotlib
- seaborn
- reportlab
- scikit-learn
- pyautogui
- colorama
- PyPDF2
- pytube
- requests
- beautifulsoup4
- scapy
- python-nmap

These libraries are essential for various functionalities within HounaarToolkit.

You can install them via the command below:
```bash
pip install -r req.txt
```

## Contributing

If you'd like to contribute to HounaarToolkit, please open an issue or submit a pull request on our GitHub repository. We welcome contributions and suggestions from the community.

## License

HounaarToolkit is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
