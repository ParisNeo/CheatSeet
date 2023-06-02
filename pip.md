pip install package_name                    # Install a package
pip install package_name==version           # Install a specific version of a package
pip install --upgrade package_name          # Upgrade a package to the latest version
pip uninstall package_name                  # Uninstall a package
pip search search_term                      # Search for packages
pip show package_name                       # Show information about a package
pip list                                   # List installed packages
pip freeze                                 # Output installed packages in requirements format
pip freeze > requirements.txt              # Save installed packages to a requirements file
pip install -r requirements.txt             # Install packages from a requirements file
pip install --proxy proxy_server package_name  # Install a package using a proxy server
pip install --trusted-host hostname package_name  # Install a package from an untrusted host
pip install --no-cache-dir package_name     # Install a package without caching
pip install --pre package_name              # Install pre-release or development version of a package
pip install --editable path_to_package      # Install a package in editable mode from a local directory
pip download package_name                   # Download a package without installing it
pip wheel package_name                      # Build a wheel distribution from a package
pip install package_name.whl                # Install a package from a wheel file
pip check                                  # Verify installed packages have compatible dependencies
pip config list                            # List pip configuration settings
pip config get key                          # Get the value of a specific pip configuration key
pip config set key value                    # Set the value of a specific pip configuration key
pip config unset key                        # Unset a specific pip configuration key
pip config --editor                         # Open the configuration file in an editor