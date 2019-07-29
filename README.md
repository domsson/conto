# conto - conversion tools

A set of very simple Python scripts that help you quickly convert common web units into each other - right from within your terminal. No need to navigate to ad-ridden conversion websites anymore. Yay!

## Usage

Make sure all scripts are executable via `chmod +x script-name`. Then run them like `./script-name`.

## Example

Convert 16 px to em/rem, pt and %:

    ./px2all 16

Convert 0.5 em/rem to px, pt and %:

    ./rem2all 0.5

## Note

Assumes a root `font-size` of `16px`. I'll add a command line option to customize this eventually. I guess.

