# CircusCircos
Scripts and singularity collection for running the Circos diagram tool

# Dependencies

Requires singularity, should work on most linux computers


# usage

Download the singularity collection

The collection contains all dependencies for running circos. Download circos:

	wget http://circos.ca/distribution/circos-0.69-6.tgz	
	tar -xvf circos-0.69-6.tgz

Run the example

	cd circos-0.69-6/example/

	singularity exec ../../circus.simg perl run

Create your own circos configs, and run in a similar fasion.
Remember to only use relative path within your circos config, otherwise, singularity will resolve within the container.


