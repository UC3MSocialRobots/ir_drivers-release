cmake_minimum_required(VERSION 2.8.3)
project(ir_drivers)

# install third parties
execute_process(COMMAND sudo bash install.bash
    WORKING_DIRECTORY ${PROJECT_SOURCE_DIR}/irtrans/IRTrans_shlib/
)
