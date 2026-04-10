

## installing  a virtual environment!

**ATTENTION:** If you don't already have python3 installed, make sure to do that!
but if you're also using the raspberry pi zero 2w it should be preinstalled!

### Process

- **step 1** run an update on your package manager, just in case

```
sudo apt update
```

- **step 2** install the ability to make virtual environments.

```
sudo apt install python3-venv
```
- **step 3** now create your virtual environment!

```
python3 -m venv example
```

- **step 4** entering your virtual environment!

```
source example/bin/activate
```
- **step 5** now you're done! yay!

if you want **to leave** the virtual environment then you must **type deactivate**.
