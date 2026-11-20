# AI in Biology Workshop

## Live Demo — Comparing Cells From the Same Donor

Can we use a plot to see how average APOBEC3A expression differs within each donor?

The demo uses synthetic data from six donors. Each donor has two values for the same gene, APOBEC3A. One is the average expression in basal tumor cells with detectable HPV16 RNA. The other is the average in basal tumor cells where HPV16 RNA was not detected.

### Run the demo

1. Download [demo_data.csv](demo_data.csv).
2. Open a new ChatGPT conversation and upload the CSV.
3. Open [demo_prompt.txt](demo_prompt.txt), copy the prompt, and paste it into the chat.
4. Check that the plot has one line per donor, for a total of six lines.

### Check one result by hand

For donor D01, the average expression is 2.0 in the HPV16 RNA undetected group and 1.2 in the detected group.

**Detected minus undetected = 1.2 − 2.0 = −0.8.**

The line for D01 should go down from left to right.

All values are made up for this teaching exercise.
