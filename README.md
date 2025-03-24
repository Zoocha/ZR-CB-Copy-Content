# Zoocha Copy Content Installation Guide

To install the Zoocha Copy Content, follow the steps below:

1. Open your terminal.
2. Navigate to your project directory.
3. Add the below in the Drupal Root's composer.json installer-paths
    ```sh
    "web/recipes/custom/{$name}": ["type:drupal-recipe"]
    ```
4. Run the following command to execute the Zoocha Copy Contentinstallation:

    ```sh
    ddev drush recipe recipes/custom/zr-cb-copy-content
    ```

This command will execute the Zoocha Copy Content installation.
