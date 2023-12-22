# bitcoin-links

https://bitcoinmedia.id/cara-membuat-cryptocurrency-sendiri/


https://git.davepedu.com/dave/docker-cagecoin/commit/52dee379165ad79f12b2f2021fe3c10b1fc81902.diff

https://github.com/vinced/namecoin/tree/mergedmine

=======================
```js

sudo apt-get install git
sudo apt-get install build-essential libtool autotools-dev automake pkg-config libssl-dev libevent-dev bsdmainutils
sudo apt-get install libboost-system-dev libboost-filesystem-dev libboost-chrono-dev libboost-program-options-dev libboost-test-dev libboost-thread-dev
sudo apt-get install libboost-all-dev
sudo apt-get install software-properties-common
sudo add-apt-repository ppa:bitcoin/bitcoin
sudo apt-get update
sudo apt-get install libdb4.8-dev libdb4.8++-dev
sudo apt-get install libminiupnpc-dev
sudo apt-get install libzmq3-dev
sudo apt-get install libqt5gui5 libqt5core5a libqt5dbus5 qttools5-dev qttools5-dev-tools libprotobuf-dev protobuf-compiler
sudo apt-get install libqt4-dev libprotobuf-dev protobuf-compiler

```

```js


cd Desktop
git clone -b 0.8 https://github.com/litecoin-project/litecoin.git
```
```js

cd ebina
find . -type f -print0 | xargs -0 sed -i 's/litecoin/ebina/g'
find . -type f -print0 | xargs -0 sed -i 's/Litecoin/Ebina/g'
find . -type f -print0 | xargs -0 sed -i 's/LiteCoin/EbinaCoin/g'
find . -type f -print0 | xargs -0 sed -i 's/LITECOIN/EBINA/g'
find . -type f -print0 | xargs -0 sed -i 's/LTC/INA/g'

```
```js
const CScriptID& hash = boost::get<CScriptID>(address);
```
```js
make -f makefile.unix
```
```js

find . -type f -print0 | xargs -0 sed -i 's/9333/2333/g'
find . -type f -print0 | xargs -0 sed -i 's/9332/2332/g'

```

```js
class CBitcoinAddress : public CBase58Data
{
public:
enum
{
PUBKEY_ADDRESS = 33, // Ebina addresses start with E
SCRIPT_ADDRESS = 5,
PUBKEY_ADDRESS_TEST = 92,
SCRIPT_ADDRESS_TEST = 196,
};
```
```js
openssl ecparam -genkey -name secp256k1 -out alertkey.pem
openssl ec -in alertkey.pem -text > alertkey.hex
openssl ecparam -genkey -name secp256k1 -out testnetalert.pem
openssl ec -in testnetalert.pem -text > testnetalert.hex
openssl ecparam -genkey -name secp256k1 -out genesiscoinbase.pem
openssl ec -in testnetalert.pem -text > genesiscoinbase.hex
```
```js

cat alertkey.hex
```


```js
04:9b:94:c8:19:40:a0:58:6a:5e:d7:0a:1a:56:63:
cf:02:e8:58:b0:22:8f:57:0f:99:a9:ef:a5:9f:61:
92:c9:98:eb:ab:a7:f7:2c:58:d2:d3:57:c6:6b:01:
d5:d0:0b:97:35:5e:c5:a4:55:07:5f:8b:31:f8:4e:
82:22:22:48:77

```
```js
049b94c81940a0586a5ed70a1a5663
cf02e858b0228f570f99a9efa59f61
92c998ebaba7f72c58d2d357c66b01
d5d00b97355ec5a455075f8b31f84e
4322224877



```js
sudo apt-get install git
sudo apt-get install build-essential libtool autotools-dev automake pkg-config libssl-dev libevent-dev bsdmainutils
sudo apt-get install libboost-system-dev libboost-filesystem-dev libboost-chrono-dev libboost-program-options-dev libboost-test-dev libboost-thread-dev
sudo apt-get install libboost-all-dev
sudo apt-get install software-properties-common
sudo add-apt-repository ppa:bitcoin/bitcoin
sudo apt-get update
sudo apt-get install libdb4.8-dev libdb4.8++-dev
sudo apt-get install libminiupnpc-dev
sudo apt-get install libzmq3-dev
sudo apt-get install libqt5gui5 libqt5core5a libqt5dbus5 qttools5-dev qttools5-dev-tools libprotobuf-dev protobuf-compiler
sudo apt-get install libqt4-dev libprotobuf-dev protobuf-compiler
```

<p>Kalau sudah, lanjutkan dengan merubah semua nama Litecoin, menjadi apapun sesuka anda. Paste saja perintah dibawah ini:</p><pre class="wp-block-code "><code>cd ebina
find . -type f -print0 | xargs -0 sed -i 's/litecoin/ebina/g'
find . -type f -print0 | xargs -0 sed -i 's/Litecoin/Ebina/g'
find . -type f -print0 | xargs -0 sed -i 's/LiteCoin/EbinaCoin/g'
find . -type f -print0 | xargs -0 sed -i 's/LITECOIN/EBINA/g'
find . -type f -print0 | xargs -0 sed -i 's/LTC/INA/g'</code>
<pre class="wp-block-code "><code>class CBitcoinAddress : public CBase58Data
{
public:
enum
{
PUBKEY_ADDRESS = 33, // Ebina addresses start with E
SCRIPT_ADDRESS = 5,
PUBKEY_ADDRESS_TEST = 92,
SCRIPT_ADDRESS_TEST = 196,
};</code>
<pre class="wp-block-code "><code>openssl ecparam -genkey -name secp256k1 -out alertkey.pem
openssl ec -in alertkey.pem -text &gt; alertkey.hex
openssl ecparam -genkey -name secp256k1 -out testnetalert.pem
openssl ec -in testnetalert.pem -text &gt; testnetalert.hex
openssl ecparam -genkey -name secp256k1 -out genesiscoinbase.pem
openssl ec -in testnetalert.pem -text &gt; genesiscoinbase.hex</code>
public key</span>, paste di text editor anda, lalu hilangkan tanda &ldquo;:&rdquo;, dan jadikan dalam satu baris saja. Sebagai contoh, dari public key yang semula seperti ini:</p><pre class="wp-block-code "><code>04:9b:94:c8:19:40:a0:58:6a:5e:d7:0a:1a:56:63:
cf:02:e8:58:b0:22:8f:57:0f:99:a9:ef:a5:9f:61:
92:c9:98:eb:ab:a7:f7:2c:58:d2:d3:57:c6:6b:01:
d5:d0:0b:97:35:5e:c5:a4:55:07:5f:8b:31:f8:4e:
82:22:22:48:77</code></pre><p>Lalu hapus tanda &ldquo;<strong>:</strong>&rdquo; hingga seperti ini:</p><pre class="wp-block-code "><code>049b94c81940a0586a5ed70a1a5663
cf02e858b0228f570f99a9efa59f61
92c998ebaba7f72c58d2d357c66b01
d5d00b97355ec5a455075f8b31f84e
4322224877</code></pre
			 <code>if (false &amp;&amp; block.GetHash() != hashGenesisBlock)
        {
            printf("Searching for genesis block...\n ");
            // This will figure out a valid hash and Nonce if you're
            // creating a different genesis block:
            uint256 hashTarget = CBigNum().SetCompact(block.nBits).getuint256();
            uint256 thash;
            char scratchpad[SCRYPT_SCRATCHPAD_SIZE];
 
            loop
            {
#if defined(USE_SSE2)
                // Detection would work, but in cases where we KNOW it always has SSE2,
                // it is faster to use directly than to use a function pointer or conditional.
#if defined(_M_X64) || defined(__x86_64__) || defined(_M_AMD64) || (defined(MAC_OSX) &amp;&amp; defined(__i386__))
                // Always SSE2: x86_64 or Intel MacOS X
                scrypt_1024_1_1_256_sp_sse2(BEGIN(block.nVersion), BEGIN(thash), scratchpad);
#else
                // Detect SSE2: 32bit x86 Linux or Windows
                scrypt_1024_1_1_256_sp(BEGIN(block.nVersion), BEGIN(thash), scratchpad);
#endif
#else
                // Generic scrypt
                scrypt_1024_1_1_256_sp_generic(BEGIN(block.nVersion), BEGIN(thash), scratchpad);
#endif
                if (thash &lt;= hashTarget)
                    break;
                if ((block.nNonce &amp; 0xFFF) == 0)
                {
                    printf("nonce %08X:hash=%s (target=%s)\n ", block.nNonce, thash.ToString().c_str(), hashTarget.ToString().c_str());
                }
                ++block.nNonce;
                if (block.nNonce == 0)
                {
                    printf("NONCE WRAPPED,incrementing time\n ");
                    ++block.nTime;
                }
            }
            printf("block.nTime=%u \n ", block.nTime);
            printf("block.nNonce=%u \n ", block.nNonce);
            printf("block.GetHash=%s\n ", block.GetHash().ToString().c_str());
        }</code></pre>
	
