# fitting command
humor/fitting/run_fitting.py @./config/fit_rgb_demo_no_split.cfg --openpose ../openpose-master

# visualize fitting

humor/fitting/vis_fitting_rgb.py --result ./output --out ./output_vis --vis-prio-frame
