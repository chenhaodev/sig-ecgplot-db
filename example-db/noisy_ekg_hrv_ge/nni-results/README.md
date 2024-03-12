This folder contains nni based analytic result that predict potential arrhythmias. 

* art: alert for noise, detected by `sig-ecgplot/examples/noisy_ekg_hrv_ge/step1_noise_spike_detect.py`
* nni: nn-intervals, calculated by `sig-ecgplot/examples/noisy_ekg_hrv_ge/step2_nn_intervals_gen.py`
* nna: nn-intervals histogram analytic results for each segment (exclude noise periods)
* nni-arrhy-v1.csv: for each segment, if multi nn-interval distributions are found, we claim it as potential arrhy period.
