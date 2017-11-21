# Model detail and summary

 * Pre-process
- [ ] write picture transform function again 
	- [ ] confirm seg pic channel is ok
	- [x] numpy 
	- [x] save png/jpg 
	- [x] mirror the pic
	- [x] save mask 
	- [x] resize to given size and save
	- [x] save to disk

 * Cheer up
- I nearly rewrite all construct for python convert dicom, not big thing, but really help with daily use 

 * DeepMask
- [ ] refind code for influence
- [x] add fc or other net
	- learning rate 0.1 and loss crash from 100+ to 2, network is too much
	- after add 3 fc, the net is working well
- [x] find a good learning rate 
	- come to table see the detail, model impression limiated 
- [x] add iou loss for classify
	- tf.onehot, slice the tensor

 * SegNet
- [ ] 
- [x] SegNet tutorial is running

