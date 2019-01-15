--------------
Training set
--------------
TrainingSet_ contains two text files : *train_index.dat* and *train_labels.dat*.

*train_index.dat* contains the path of training patterns in raw dataset. For example:
::
	amo86615_190_190_class_v1.h5,309

means this is the 309*th* pattern in file *amo86615_190_190_class_v1.h5*.

*train_labels.dat* contains training labels of patterns, where '1' means the pattern is a single-hit pattern, '0' means not.


---------------
validation set
---------------
ValidationSet_ contrains a HDF5 file 'validation.h5'. There are 500 patterns, with their labels and path in it.


.. _TrainingSet: http://liulab.csrc.ac.cn/dokuwiki/lib/exe/fetch.php?media=training.zip
.. _ValidationSet: http://liulab.csrc.ac.cn/dokuwiki/lib/exe/fetch.php?media=validation.zip