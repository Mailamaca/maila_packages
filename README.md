```bash
echo "deb [trusted=yes] https://github.com/Mailamaca/maila_packages/raw/jammy-humble/ ./" | sudo tee /etc/apt/sources.list.d/Mailamaca_maila_packages.list
echo "yaml https://github.com/Mailamaca/maila_packages/raw/jammy-humble/local.yaml humble" | sudo tee /etc/ros/rosdep/sources.list.d/1-Mailamaca_maila_packages.list
```
