The program builds with make and produces bin/boxes. Example usage (interactive):

# build
make


# run sample demo
./bin/boxes demo


# add entries
./bin/boxes add static 2025-12-01 "Sensor A reading"
./bin/boxes add dynamic 2025-11-30 "Sensor B reading"


# fetch
./bin/boxes get static 2025-12-01
./bin/boxes range dynamic 2025-11-01 2025-12-31
