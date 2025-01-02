# QML-for-LHCb-distinguish-real-tracks-from-ghosts

The LHCb experiments at CERN collect data from high-energy particle collisions, in order to
discover potential new fundamental particles and forces of nature. The probability of creating
interesting events is low, hence 40 million particle bunches will be collided each second,
yielding a data throughput of 40 Tbps. This poses an enormous data challenge. Since it would
be unrealistic to store all data coming from the experiment, fast algorithms do a filtering
process in soft real-time, in a two-stage process known as High-Level Trigger. Potentially
interesting events are filtered out in real-time by this trigger system. The demands on such a
system are large in terms of efficiency, false positive rate and speed, so we wish to investigate
if this can be done in a novel way with QML algorithms. In this project, the goal will be to
implement a quantum Support Vector Machine algorithm and test it with track information
to distinguish real tracks from ghosts, trajectories created from combinations of random hits
that together look like a real trajectory. In the first phase of the project, you are free to explore
other quantum ML algorithms that would be possible to use for the ghosts recognition.
For more details, see
https://arxiv.org/pdf/1804.11326.pdf
https://arxiv.org/pdf/2012.07725.pdf
https://qiskit.org/documentation/stable/0.24/tutorials/machine_learning/01_qsvm_classification.ht
ml
https://arxiv.org/pdf/1912.09161.pdf
