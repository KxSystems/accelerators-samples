# Accelerator Sample Notebooks

The Accelerator notebook samples demonstrate accessing kdb Accelerator APIs via REST. These examples can be used as-is in Python, but similar queries can be performed from any REST-capable language or system.

## kdb Accelerators

kdb Accelerators are packages for kdb products that address typical industry use cases. Using an Accelerator allows you to leapfrog the first phases of a project or Insights implementation, skipping common boilerplate or initial effort and jumping straight to value adding work. They are a customization-first approach to developing on kdb products, helping you learn and unlock the value of KX products faster.

More information on kdb Accelerators, which use cases are available, and their associated documentation is available on [code.kx.com](https://code.kx.com/insights/accelerators).

## Available notebooks

The following Accelerator notebooks are available:

- [ICE Orderbook](https://github.com/KxSystems/accelerators-samples/ICE-OrderBook)
- [ICE Fixed Income](https://github.com/KxSystems/accelerators-samples/ICE-Fixed-Income)

## Installation

1. The necessary pip installs are available in a `requirements.txt` in each directory.

    (optional) To see a comprehensive list of requirements, see the `requirements.txt` file in the repository.

    ```bash
    pip install -r requirements.txt
    ```

## View & Execute The Samples

Samples can be run directly in Visual Studio Code using the Jupyter plugin, or run with the `jupyter` package installed for Python. For more information on installing Jupyter, see the [VS Code](https://github.com/microsoft/vscode-jupyter) or [Jupyter documentation](https://jupyter.org/install).

1. Run a Jupyter notebook session:

    ```bash
    jupyter notebook --no-browser
    ```

    This will load up the jupyter session in the background and display a URL on screen for you.

1. Paste this URL into your browser

    This will bring up the samples for you to interact with.