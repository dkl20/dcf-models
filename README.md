# dcf-models
The Discounted Cash Flow (DCF) models in this repository apply the principles of Net Present Value (NPV) to estimate the intrinsic value of stocks.

These models import historical quarterly and annual filings of companies, primarily focusing on their income statements to analyze revenues, expenses, and net income. Using this data, future annual net incomes are estimated and projected with either a growth or decline rate, in conjunction with a discount rate, both of which are used in the NPV calculation.

By applying the discount rate to the projected annual net incomes, adjusting for their growth or decline rate, and factoring in the company’s cash and debt (including current and long-term convertible senior notes - because of principal and interest repayments), the NPV is calculated. Dividing the resulting NPV by the current outstanding shares provides the intrinsic value of the stock, which can be used as a holistic metric for evaluating a company's viability as an investment.
