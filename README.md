VPN to Socket
===========

Quick and easy VPN to Socket using packet manipulation. Create proxys and firewalls easily globally!

How can I create a proxy or firewall within this library? 
-----------
All you need to do is modify the ```VPN/Proxy.java``` file.

How it works
-----------
We take the first byte as we would with a regular socks proxy and check if the byte is C/G/P aka first byte for the HTTP/HTTPS protocol. We then route the socket through a simple HTTP/HTTPS proxy if it matches, if not it gets routed over SOCKS.

License
-----------
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, TITLE AND NON-INFRINGEMENT. IN NO EVENT SHALL THE COPYRIGHT HOLDERS OR ANYONE DISTRIBUTING THE SOFTWARE BE LIABLE FOR ANY DAMAGES OR OTHER LIABILITY, WHETHER IN CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE
