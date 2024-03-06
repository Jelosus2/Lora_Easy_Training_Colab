# Lora_Easy_Training_Colab

A colab powered by [Lora_Easy_Training_Scripts_Backend](https://github.com/derrian-distro/LoRA_Easy_Training_scripts_Backend) created by [Derrian Distro](https://github.com/derrian-distro)

### The Forked version of the trainer is not maintained by Derrian, please do not open issues there if you encounter any problem. Instead submit them in the [forked repo](https://github.com/Jelosus2/LoRA_Easy_Training_scripts_Backend/).

## Guide

You can check the [guide I made on CivitAI]() (TODO: Add link once redacted)

## Table of content

- [Additions of the Forked version](#additions-of-the-forked-version)
- [How to install the UI](#how-to-install-the-ui)
  - [Windows](#windows)
  - [Linux](#linux)
- [How to get the link for custom model/VAE]()

## Additions of the Forked version

The forked trainer is a modified unofficial version that adds additional features.

The list of addition features:
- Optimizers:
  - CAME
- Schedulers:
  - REX 

## How to install the UI

### Windows

Prerequisites:
- Download and install [Git](https://git-scm.com/downloads)
- Download and install [Python 3.10.9](https://www.python.org/downloads/release/python-3109/#:~:text=Full%20Changelog-,Files,-Version)

#### Original

Open a command line or PowerShell and run this commands in order
```
git clone -b dev https://github.com/derrian-distro/LoRA_Easy_Training_Scripts
cd LoRA_Easy_Training_Scripts
install.bat
```
When you run `install.bat` answer the question "Are you using this locally?" with **n**

To run the UI use the `run.bat`

#### Forked

Open a command line or PowerShell and run this commands in order
```
git clone https://github.com/Jelosus2/LoRA_Easy_Training_Colab_Frontend
cd LoRA_Easy_Training_Colab_Frontend
install.bat
```

To run the UI use the `run.bat`

### Linux

Prerequisites:
- Install Git with `sudo apt install git`
- Install Python 3.10 venv with `sudo apt install python3.10-venv`

#### Original

Open a terminal and run the following commands in order
```
git clone -b dev https://github.com/derrian-distro/LoRA_Easy_Training_Scripts
cd LoRA_Easy_Training_Scripts
python3.10 ./install.py
```

When you run the installer answer the question "Are you using this locally?" with **n**

To run the UI first you have to give permissions to the `run.sh` file, here is an example:
```
sudo chmod 755 ./run.sh
```
and then you can run the UI with
```
./run.sh
```

#### Forked

Open a terminal and run the following commands in order
```
git clone https://github.com/Jelosus2/LoRA_Easy_Training_Colab_Frontend
cd LoRA_Easy_Training_Colab_Frontend
python3.10 ./install.py
```

To run the UI first you have to give permissions to the `run.sh` file, here is an example:
```
sudo chmod 755 ./run.sh
```
and then you can run the UI with
```
./run.sh
```