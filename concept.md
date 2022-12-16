
**Goals:** My goal for this project is to be able to see how much power is wasted when battery-powered devices are left on the charger after they are fully charged.

**Context:** There exist products that can be put in-line with a device being charged via USB in order to read voltage and current, but none exist that specifically keep track of total power consumption nor do any keep track of whether or not the device is fully charged. My idea is specifically to detect when a device is fully charged, but still drawing a small amount of power in order to maintain a 100% charge status.

**Novelty:** The novelty of my product is that by simply connecting it between a power source and a target device to be charged, the user will be able to read these data metrics.

**Functionality:** The expected functionality is to take current and voltage measurements from the connection between a device and a power adapter. It should detect when the device enters the lower power charging mode dur to a full battery and then add up all of that power in order to track how much is wasted.

**Audience:** My product is mostly meant for curious people, but it certainly possible that I discover the amount of power being wasted is significant enough to matter to some people.

**Challenges:** I expect challenges from the level of precision from the current sensor I am using, as well as possible issues with the speed with which it pulls information. I will also need to do some clever math in order to detect the different charging states of the device.

**Measures:** If my project can switch to recording total power consumed once a device that is connected reaches full charge, I will consider that a successful implementation of my idea.

**Motivation:** My motivation is the fascination with the way we see resources. There are many ways that most people are aware that they are being wasteful of resources, but there are also lesser known wasteful practices that we participate in every day. I would like to see just how wasteful this habit might be, though I am prepared to discover a very underwhelming conclusion.

**Future Extensions:** In the future, I would like my product to be a compact, standalone device rather than an entire small computer with an attached sensor and a ciruit on a breadboard. I would also like it to send the data it collects to the cloud so that the user may look it over whenever it is convenient.


