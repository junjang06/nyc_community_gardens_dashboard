# NYC Community Gardens for Equitable Climate Resilience

A Streamlit dashboard that treats NYC community gardens as small-scale urban resilience infrastructure connected to SDG 11, SDG 13, SDG 15, and supporting SDG 2 and SDG 3.

## Files

- `app.py` — full Streamlit app
- `requirements.txt` — package dependencies
- Optional: `data/nta_population.csv` — recommended production population file with columns `nta_code`, `nta_name`, `population`

## Run locally

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Deploy on Streamlit Community Cloud

1. Create a GitHub repository.
2. Upload `app.py` and `requirements.txt` to the repository root.
3. Optional but recommended: add `data/nta_population.csv` with clean 2020 NTA population denominators.
4. Go to Streamlit Community Cloud and choose **New app**.
5. Select the repository, branch, and set main file path to `app.py`.
6. Deploy.

## Data caveats

This dashboard is exploratory and educational. It does not estimate causal effects of community gardens on health outcomes. For formal analysis, verify population denominators, HVI geography compatibility, garden status/operating access, and walking-network access.
