# Weather-forecasting-links-n-docs

Thesis submitted - https://drive.google.com/file/d/1Do9NGz8wEe1ETCaNr1UEn__Sd--5DT02/view?usp=sharing

Models created - https://drive.google.com/drive/folders/195g_X-cdNyCiBrfRRBspFPa1Cg_k9MSl?usp=sharing


## High Level Summary
- Data Pipeline: Developed a forecasting pipeline in Python, leveraging the NREL API to ingest and process 5 years of historical wind data (43,000+ records).
- Data Denoising: Implemented Ensemble Empirical Mode Decomposition (EEMD) to perform advanced signal denoising and decomposition, to isolate Intrinsic Mode Functions (IMFs) from non-stationary, noisy data.
- Model Architecture: Architected a sliding-window supervised learning system to benchmark nine models; the EEMD-CNN hybrid model achieved a 4.7% MAPE, significantly reducing forecasting errors compared to baseline LSTM models.
