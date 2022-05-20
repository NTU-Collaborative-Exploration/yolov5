clone from https://github.com/ultralytics/yolov5.git
  commit 7c6a33564a84a0e78ec19da66ea6016d51c32e0a

修改 import 为完整路径, e.g.
  -from utils.general import LOGGER, file_update_date, git_describe
  +from yolov5.utils.general import LOGGER, file_update_date, git_describe

