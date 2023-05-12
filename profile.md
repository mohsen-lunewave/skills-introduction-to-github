global preparam;  % Preprocessor parameters
addpath 'Functions'
cfar_method=2;  %1:baseline, 2:med
preparam.cfar_method=cfar_method;
fpga_config_IncreaseDopNum_CleanUp();
