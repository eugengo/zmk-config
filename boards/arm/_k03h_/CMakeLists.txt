zephyr_library()
zephyr_include_directories(.)
board_set_flasher_ifnset(rp2040.uf2)

