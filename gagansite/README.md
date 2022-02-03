# Commands

hugo new site site_name - Initialize the Site
git init - Parent of the site_name
Change config.toml
	Update base URL to github URL (NOTE: Use / as the root url - Fixes theme issues)
	Add theme='theme_name' in the end
hugo server - To test the site
git submodule add -b main git_repo_url public - To create submodul
hugo -t theme_name - To generate stuff in the public directory
hugo new post/post_name.md - To create new post