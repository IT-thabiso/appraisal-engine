LIVE

# Investment Appraisal Workbench

A single capital project, evaluated by net present value, internal rate of return, payback and the profitability index, and discounted at a cost of capital built from the Capital Asset Pricing Model.

Look:

**Exhibit 1.** *Project assumptions*

| Currency symbol |  |  |
| --- | --- | --- |
| Initial capital outlay (year 0) |  | currency |
| Project life |  | years, 3 to 10 |
| Revenue in year 1 |  | currency |
| Revenue growth |  | % per year |
| Operating costs |  | % of revenue |
| Working capital required |  | % of revenue |
| Scrap value at end of life |  | currency |
| Company tax rate |  | % |

**Exhibit 2.** *Pro-forma cash flow schedule*

Cells shaded and underlined are inputs and may be overwritten. Changing an assumption in Exhibit 1 rebuilds the rows.

**Exhibit 4.** *Decision metrics*

**Figure 1.** *Net present value profile*

NPV of the project at each discount rate. The curve crosses zero at the internal rate of return; the dashed line marks the rate used here.

**Exhibit 3.** *Cost of capital*

Ke = Rf + β × MRP

| Risk-free rate |  | % |
| --- | --- | --- |
| Equity beta (β) |  |  |
| Market risk premium |  | % |
| Cost of equity |  |  |

WACC = (E/V)Ke + (D/V)Kd(1 − T)

| Equity weight, E/V |  | % |
| --- | --- | --- |
| Debt weight, D/V |  | % |
| Pre-tax cost of debt |  | % |
| After-tax cost of debt |  |  |
| WACC |  |  |

Discount the project at

| Discount rate |  | % |
| --- | --- | --- |

**Exhibit 5.** *Saved projects*

**Notes**

1. NPV = Σ CFt / (1 + r)t, summed from t = 0 to n. Cash flows arrive at the end of each year; the capital outlay occurs at t = 0.
2. Depreciation is straight line from cost to scrap value, so the asset’s book value equals its scrap value at the end of life and no balancing tax arises. Tax is charged on profit before tax, assuming the company can use any losses.
3. Working capital is a share of revenue. Increases are deducted as they occur and the full balance is recovered in the final year.
4. The IRR is the rate at which NPV equals zero, found numerically by bisection. It is not reported when the cash flows do not change sign. Payback is interpolated within the year in which cumulative cash flow turns positive.
5. Profitability index = present value of cash flows from years 1 to n divided by the initial outlay.
6. This online preview runs the server’s finance code inside your browser, and saved projects stay in this browser only. The downloadable version runs the same code on a Node server.
7. Results depend entirely on the estimates entered. This is a teaching and decision-support tool and not financial advice.