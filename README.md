# Default theme for VirtoCommerce Demo

This is a fork of default theme for using on demo.virtocommerce.com site.

To merge changes from default theme, follow this instructions:
1. `git clone https://github.com/VirtoCommerce/vc-demo-theme.git "C:\Repos\vc-demo-theme"` - clone repo
2. `git remote add upstream https://github.com/VirtoCommerce/vc-default-theme.git` - add upstream
3. `git fetch --all` - fetch changed from both repos
4. `git merge upstream/master --allow-unrelated` - merge changes from default theme to theme for demo site
