# MA_trading-strategy

> Warren Buffett: For most people, the best thing to do is owning a index fund.

Yes, good suggestion, and we will try to beat that in this project.
This page is a short demo. For details, please refer to the notebook.
***

The baseline we are comparing here is the DCA strategy, which is the simplest strategy an investor can do (invest a sum of money over a fixed period of time, usually after they receive their pay each month).

## Developing trading strategy: 
Trades according to the moving average. Prevents losses during the bear market, but also misses the explosive growth of the bull market. 
<p float="left">
  <img src="Line chart results/phase1_1yr.png" width="45%" />
  <img src="Line chart results/phase1_2yr.png" width="45%" />
  <img src="Line chart results/phase1_3yr.png" width="45%" />
</p>

## Improving the strategy: 
Switch between DCA and MA trading strategies depending on the bull/bear market. Proven effective. Could improve bull/bear market identification.
<p float="left">
  <img src="Line chart results/phase2_1yr.png" width="45%" />
  <img src="Line chart results/phase2_2yr.png" width="45%" />
  <img src="Line chart results/phase2_3yr.png" width="45%" />
</p>

## Improving bull/bear market identification: 
A significant improvement has been seen. The next step is to fine-tune the parameters.
<p float="left">
  <img src="Line chart results/phase3_1yr.png" width="45%" />
  <img src="Line chart results/phase3_2yr.png" width="45%" />
  <img src="Line chart results/phase3_3yr.png" width="45%" />
</p>

## Fine-tuning and the final results: 
Pretty promising findings.
<p float="left">
  <img src="Line chart results/tuned_1yr.png" width="45%" />
  <img src="Line chart results/tuned_2yr.png" width="45%" />
  <img src="Line chart results/tuned_3yr.png" width="45%" />
</p>
