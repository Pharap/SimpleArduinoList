# SimpleArduinoList
A very simple list class that can store no more than 128 items, intended for use in embedded system environments with very little RAM. Has only copy semantics, not move semantics, due to the absence of std::move and std::remove_reference in Arduino environments.
