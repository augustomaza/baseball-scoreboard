# baseball-scoreboard
Build your own baseball scoreboard using Raspberry Pi with WiFi and Johnny-Five software library

This is based on scoreboard at https://buildyourownscoreboard.wordpress.com/
The code here is specific to a baseball scoreboard.

This scoreboard only uses the raspberry pi hardware and home made seven segment led numbers.
The software included here is johnny-five software with changes specific to using +12V Common Anode wiring connections and using the TPIC6B595 and TPIC6A595 Shift Register chips.

1. Install Raspbian on the Raspberry Pi 3 (google to find instructions)

2. curl -sL https://deb.nodesource.com/setup_9.x | sudo -E bash -

3. sudo apt-get install -y nodejs

4. mkdir johnny-five

5. git clone git://github.com/rwaldron/johnny-five.git

6. cd johnny-five

7. npm install


MORE COMING SOON
