# credit_spread

The Credit Spread Model in fixed income refers to the difference in yield between a corporate bond and a risk-free government bond of similar maturity. This spread compensates investors for the additional risk of default associated with corporate bonds. Below, I'll explain the key concepts and provide the equations in ASCII text format.

1. Credit Spread Calculation
The credit spread is the difference between the yield on a corporate bond and the yield on a risk-free bond (typically a government bond). It is calculated as:
Credit Spread = Corporate Bond Yield - Risk-Free Yield

2. Credit Spread Curve
A credit spread curve represents the credit spread across different maturities. For a given set of corporate bond yields and corresponding risk-free bond yields, the credit spread curve can be defined as:
Credit Spread Curve = [Spread_1, Spread_2, ..., Spread_n]
Where:
Spread_i = Corporate Bond Yield_i - Risk-Free Yield_i

4. Bond Pricing Adjustment Due to Credit Spread
The price of a bond can be adjusted to account for the credit spread. The adjusted bond price is the present value of the bond's cash flows (coupons and face value) discounted at the yield that includes the credit spread. The formula is:
Adjusted Bond Price = (Coupon / (1 + Adjusted Yield)^1) + (Coupon / (1 + Adjusted Yield)^2) + ... + (Face Value / (1 + Adjusted Yield)^n)
Where:
Adjusted Yield = Risk-Free Yield + Credit Spread

4. Spread to Default Probability
The implied default probability can be estimated from the credit spread using simplified models. One such model is based on the assumption that the credit spread compensates for the expected loss due to default:
Default Probability = Credit Spread / ((1 - Recovery Rate) * Volatility)
Where:
Recovery Rate = Proportion of the bond's value that is recovered in the event of default
Volatility = Volatility of the bond's yield

5. Spread Sensitivity Analysis
Spread sensitivity analysis measures how the price of a bond changes in response to a change in the credit spread. The change in bond price due to a change in spread is calculated as:
Price Change = Adjusted Bond Price with New Spread - Adjusted Bond Price with Initial Spread
Where:
New Spread = Initial Spread + Delta Spread


Credit Spread:
Credit Spread = Corporate Bond Yield - Risk-Free Yield

Credit Spread Curve:
Credit Spread Curve = [Spread_1, Spread_2, ..., Spread_n]
Spread_i = Corporate Bond Yield_i - Risk-Free Yield_i

Adjusted Bond Price:
Adjusted Bond Price = (Coupon / (1 + Adjusted Yield)^1) + (Coupon / (1 + Adjusted Yield)^2) + ... + (Face Value / (1 + Adjusted Yield)^n)
Adjusted Yield = Risk-Free Yield + Credit Spread

Default Probability:
Default Probability = Credit Spread / ((1 - Recovery Rate) * Volatility)

Price Change Due to Spread Change:
Price Change = Adjusted Bond Price with New Spread - Adjusted Bond Price with Initial Spread
