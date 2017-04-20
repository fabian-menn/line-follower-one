# Sobrato Line Follower Robot for Robogames 2017

# Usage

## SSH

If you are cconnected directly to the robot skip this step.

	ssh <robot-ip-address> -l pi

## Update Code and Run
	
	go get github.com/sobratoftc/line-follower-one
	cd ~/robot/src/github.com/sobratoftc/line-follower-one/
	go install
	line-follower-one
