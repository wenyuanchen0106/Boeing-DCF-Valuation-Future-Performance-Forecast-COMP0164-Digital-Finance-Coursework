# Boeing Future Performance Valuation (DCF Model)
This repository contains the Python implementation used to compute Boeing’s intrinsic value for our COMP0164 Digital Finance group coursework.

The script (`BAfuturePerformance.py`) replicates the full valuation workflow from our final report, including:

### Core Features
- **WACC calculation** using CAPM  
- **Cost of debt smoothing** via multi-year averaging  
- **Normalized Free Cash Flow (FCF) estimation**  
- **5-year explicit forecast period**  
- **Terminal value calculation (Gordon Growth Model)**  
- **DCF valuation** to derive intrinsic share price  
- **Scenario analysis** (Bear / Base / Bull) modifying β, growth rate, and margins  

### Output
The script generates:
- Enterprise value and equity value  
- Intrinsic price per share  
- Scenario-based target prices  
- Sensitivity comparison with the current market price  

The calculations match the numerical results and tables presented in the “Future Performance & Valuation” section of our final report.

---

### File
