# YourShipping.Monitor-ReCaptchasDB

This is the re-captchas database for YourShipping.Monitor

## How to contrib?

YourShipping.Monitor tries to bypass the second captcha automatically, but it's depends from the published problems.

If you noticed that a new problem is generated, a new sha256 folder with a file named `!solution`, you can resolve it by adding to such file the name (without the extension) of the images. Wait for the generation of `solution-verified` file and share it with a pull request. 

