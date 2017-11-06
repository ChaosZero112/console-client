## Build steps

> sudo apt-get install cmake zlib1g-dev libboost-system-dev libboost-program-options-dev libpthread-stubs0-dev libfuse-dev git  
> mkdir console-client   
> git clone -b staging --single-branch https://github.com/ChaosZero112/console-client.git ./console-client/  
> cd ./console-client/pCloudCC/   
> cd lib/pclsync/        
> make clean    
> make fs     
> cd ../mbedtls/   
> cmake .      
> make clean     
> make       
> cd ../..      
> cmake .    
> make      
> sudo make install     
> ldconfig     
> pcloudcc -u username -p       

See the master README for more including usage.