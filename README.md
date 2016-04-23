Introducing Steem (beta)
-----------------

Steem is an experimental Proof of Work blockchain with an unproven consensus
algorithm. 

  - Currency Symbol STEEM 
  - 1.000 STEEM block reward at launch
  - Approximately 100% APR long term inflation rate

Public Announcement & Discussion
--------------------------------

Steem was announced on [Bitcointalk](https://bitcointalk.org/index.php?topic=1410943.new) prior to
any the start of any mining.  

No Support & No Warranty 
------------------------
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

Code is Documentation
---------------------

Rather than attempt to describe the rules of the blockchain, it is up to
each individual to inspect the code to understand the consensus rules.  

Seed Nodes
----------

46.252.27.1:1337
52.62.24.225:2001
192.99.4.226:2001
109.74.206.93:2001
45.55.217.111:2001
81.89.101.133:2001
52.4.250.181:39705
104.199.157.70:2001
104.236.82.250:2001
212.47.249.84:40696
162.213.199.171:34191
steem.kushed.com:2001
seed.steemed.net:2001
steem.clawmap.com:2001
steemd.pharesim.me:2001
seed.steemnodes.com:2001
seed.steemwitness.com:2001
steem-seed1.abit-more.com:2001


How to Mine
-----------

The mining algorithm used by Steem requires the owner to have access to the private key
used by the account. This means it does not favor mining pools.

    ./steemd --miner=["accountname","${WIFPRIVATEKEY}"] --witness="accountname" --seed-node="52.38.66.234:2001"

Make sure that your accountname is unique and not already used by someone else or your proof of work
might not be accepted by the blockchain.
