# EcoTrack – Project Description
**Track:** Smart & Sustainable Future

**Problem:** Households and campuses only see a monthly bill. They cannot tell whether usage is rising, what it costs the environment, or which action matters most.

**Solution:** EcoTrack forecasts next month's electricity use with least-squares regression on six months of data, estimates monthly CO₂e from electricity and landfill waste, scores sustainability 0–100, and ranks concrete actions by CO₂ saved (AC setpoint, LED switch, standby power, composting, recycling). Users can type data or import a CSV.

**Who it helps:** Families, hostels and small campuses with no energy-audit expertise.

**AI/technical approach:** Regression forecasting plus a rule-based recommendation engine with transparent assumptions (grid 0.82 kg CO₂/kWh; landfill factors organic 0.5, paper 1.0, plastic 0.2 kg CO₂e/kg). Runs fully in the browser, no keys, no backend.

**Originality:** One ranked action list that combines energy forecasting and waste footprint for non-experts.

**Limitations:** Estimates are indicative, not audits. Advice is rule-based.

**Next steps:** Smart-meter integration, LLM explanations, multi-building campus view, seasonal models.
