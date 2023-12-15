# ADA Template Website
## Usage
1. Fork (copy) this repository by clicking the "Fork" button on the top right corner.
2. Go to "Settings" -> "Pages" in your forked repository. Under "Branch" change "None" to "master" and click "Save".
3. Edit the `_config.yml` file in your forked repository to change the site title (after `title:`) and description (after `description:`).
4. Build your own page by editing this `README.md` (home page) and creating new `.md` files (other pages), formatting is done with standard [GitHub Markdown syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax), we provide an example file `example.md` in the repository.
**Important**: Please include ```--- layout: default ---``` (the first three line in `example.md`) at the beginning of your every newly created `.md` file.
5. Add your new `.md` files to the site by editing the `_config.yml` file in your forked repository. Under `navigation:` add a new pair of `- title:` and `url:`, and fill their value with your page name and `.md` file name. Remember to remove the `- title:` and `url:` pair for the example page.
6. Go back to "Settings" -> "Pages" to find your website link.

Using the CMU Movie Summary Corpus dataset, we want to dive into the drivers of an actor's success. Since the aspiration to become an actor is a dream for many, uncovering the factors or combinations of factors that contribute to an actor's accomplishment can provide valuable insights.

However, quantifying an actor's success is inherently subjective, because there are numerous ways to assess it. Some seek peer recognition through awards, others prioritize financial gains, positive ratings, public attendance, or long-lasting careers. Given these diverse goals we consider, the factors driving success may differ.

Through our analysis, we aim to offer a nuanced understanding of what drives an actor’s accomplishments. Ultimately, we want to quantify the success of actors in our dataset and allow our readers to identify the attributes maximizing a specified success metrics.
