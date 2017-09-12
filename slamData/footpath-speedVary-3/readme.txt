n2d- results are found using night-2.mp4 and day.mp4 with

range1 = np.arange(4500,12000,1) # night-2 (night2Part2.mpeg is created using these params)
range2 = np.arange(15500,21000,1) # day (dayPart2.mpeg is created using these params)

for test

and

range2 = np.arange(4000,10000,1) # day

for training the polynomial fitting function (then used for both ref and query data during test)

####################################################

n2d-2- results are found using night-2.mp4 and day.mp4 with videos cut from original sequences as

imgCounter > 12000 or imgCounter < 4500 - night2Part-1n3.mpeg

and

(imgCounter < 15500 and imgCounter > 12600) or imgCounter > 21000 - dayPart-1n3.mpeg

Training the polyfit function is done using

(imgCounter < 15500 and imgCounter > 12600) from day



