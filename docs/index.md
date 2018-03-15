<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <meta content="IE=edge,chrome=1" http-equiv="X-UA-Compatible">
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">
    <title>API Reference</title>

    <style>
      .highlight table td { padding: 5px; }
.highlight table pre { margin: 0; }
.highlight .gh {
  color: #999999;
}
.highlight .sr {
  color: #f6aa11;
}
.highlight .go {
  color: #888888;
}
.highlight .gp {
  color: #555555;
}
.highlight .gs {
}
.highlight .gu {
  color: #aaaaaa;
}
.highlight .nb {
  color: #f6aa11;
}
.highlight .cm {
  color: #75715e;
}
.highlight .cp {
  color: #75715e;
}
.highlight .c1 {
  color: #75715e;
}
.highlight .cs {
  color: #75715e;
}
.highlight .c, .highlight .cd {
  color: #75715e;
}
.highlight .err {
  color: #960050;
}
.highlight .gr {
  color: #960050;
}
.highlight .gt {
  color: #960050;
}
.highlight .gd {
  color: #49483e;
}
.highlight .gi {
  color: #49483e;
}
.highlight .ge {
  color: #49483e;
}
.highlight .kc {
  color: #66d9ef;
}
.highlight .kd {
  color: #66d9ef;
}
.highlight .kr {
  color: #66d9ef;
}
.highlight .no {
  color: #66d9ef;
}
.highlight .kt {
  color: #66d9ef;
}
.highlight .mf {
  color: #ae81ff;
}
.highlight .mh {
  color: #ae81ff;
}
.highlight .il {
  color: #ae81ff;
}
.highlight .mi {
  color: #ae81ff;
}
.highlight .mo {
  color: #ae81ff;
}
.highlight .m, .highlight .mb, .highlight .mx {
  color: #ae81ff;
}
.highlight .sc {
  color: #ae81ff;
}
.highlight .se {
  color: #ae81ff;
}
.highlight .ss {
  color: #ae81ff;
}
.highlight .sd {
  color: #e6db74;
}
.highlight .s2 {
  color: #e6db74;
}
.highlight .sb {
  color: #e6db74;
}
.highlight .sh {
  color: #e6db74;
}
.highlight .si {
  color: #e6db74;
}
.highlight .sx {
  color: #e6db74;
}
.highlight .s1 {
  color: #e6db74;
}
.highlight .s {
  color: #e6db74;
}
.highlight .na {
  color: #a6e22e;
}
.highlight .nc {
  color: #a6e22e;
}
.highlight .nd {
  color: #a6e22e;
}
.highlight .ne {
  color: #a6e22e;
}
.highlight .nf {
  color: #a6e22e;
}
.highlight .vc {
  color: #ffffff;
}
.highlight .nn {
  color: #ffffff;
}
.highlight .nl {
  color: #ffffff;
}
.highlight .ni {
  color: #ffffff;
}
.highlight .bp {
  color: #ffffff;
}
.highlight .vg {
  color: #ffffff;
}
.highlight .vi {
  color: #ffffff;
}
.highlight .nv {
  color: #ffffff;
}
.highlight .w {
  color: #ffffff;
}
.highlight {
  color: #ffffff;
}
.highlight .n, .highlight .py, .highlight .nx {
  color: #ffffff;
}
.highlight .ow {
  color: #f92672;
}
.highlight .nt {
  color: #f92672;
}
.highlight .k, .highlight .kv {
  color: #f92672;
}
.highlight .kn {
  color: #f92672;
}
.highlight .kp {
  color: #f92672;
}
.highlight .o {
  color: #f92672;
}
      * { font-family: 'Open Sans', sans-serif; }
      code { font-family: 'Inconsolata', monospace !important; font-size: 1rem !important; }
      code * { font-family: 'Inconsolata', monospace !important; font-size: 1rem !important; }
      code.block { display: block; overflow: scroll; white-space: nowrap; }
      .logo { margin: 30px auto !important; }
    </style>
    <link href="https://fonts.googleapis.com/css?family=Open+Sans|Inconsolata" rel="stylesheet">
    <link href="stylesheets/screen.css" rel="stylesheet" media="screen" />
    <link href="stylesheets/print.css" rel="stylesheet" media="print" />
      <script src="javascripts/all_nosearch.js"></script>
  </head>

  <body class="index" data-languages="[&quot;java&quot;,&quot;javascript&quot;,&quot;php&quot;,&quot;python&quot;,&quot;ruby&quot;]">
    <a href="#" id="nav-button">
      <span>
        NAV
        <img src="images/navbar.png" alt="Navbar" />
      </span>
    </a>
    <div class="toc-wrapper">
      <img src="https://www.gopax.co.kr/logo.svg" class="logo" alt="Logo" />
        <div class="lang-selector">
              <a href="#" data-language-name="java">java</a>
              <a href="#" data-language-name="javascript">javascript</a>
              <a href="#" data-language-name="php">php</a>
              <a href="#" data-language-name="python">python</a>
              <a href="#" data-language-name="ruby">ruby</a>
        </div>
      <div id="toc" class="toc-list-h1">
          <li>
            <a href="#fa255f0ccc" class="toc-h1 toc-link" data-title="">소개</a>
              <ul class="toc-list-h2">
                  <li>
                    <a href="#rest-api" class="toc-h2 toc-link" data-title="rest-api">REST API 주소</a>
                  </li>
                  <li>
                    <a href="#api" class="toc-h2 toc-link" data-title="api">API 호출 횟수 제한</a>
                  </li>
              </ul>
          </li>
          <li>
            <a href="#ce7156229f" class="toc-h1 toc-link" data-title="">인증</a>
              <ul class="toc-list-h2">
                  <li>
                    <a href="#signature" class="toc-h2 toc-link" data-title="signature">SIGNATURE 생성 과정</a>
                  </li>
                  <li>
                    <a href="#http" class="toc-h2 toc-link" data-title="http">HTTP 헤더 예제</a>
                  </li>
              </ul>
          </li>
          <li>
            <a href="#api-2" class="toc-h1 toc-link" data-title="api">인증이 필요한 API</a>
              <ul class="toc-list-h2">
                  <li>
                    <a href="#44f0674afb" class="toc-h2 toc-link" data-title="">잔액 조회하기</a>
                  </li>
                  <li>
                    <a href="#105345e7b5" class="toc-h2 toc-link" data-title="">자산 이름에 따라 잔액 조회하기</a>
                  </li>
                  <li>
                    <a href="#9a0aef758b" class="toc-h2 toc-link" data-title="">주문 조회하기</a>
                  </li>
                  <li>
                    <a href="#id" class="toc-h2 toc-link" data-title="id">주문 ID로 주문 조회하기</a>
                  </li>
                  <li>
                    <a href="#6796537949" class="toc-h2 toc-link" data-title="">주문 등록하기</a>
                  </li>
                  <li>
                    <a href="#id-2" class="toc-h2 toc-link" data-title="id">주문 ID로 주문 취소하기</a>
                  </li>
                  <li>
                    <a href="#d603331cfe" class="toc-h2 toc-link" data-title="">사용자 거래 기록 조회하기</a>
                  </li>
              </ul>
          </li>
          <li>
            <a href="#api-3" class="toc-h1 toc-link" data-title="api">인증이 필요하지 않은 API</a>
              <ul class="toc-list-h2">
                  <li>
                    <a href="#c8b9dcea10" class="toc-h2 toc-link" data-title="">자산 목록 조회하기</a>
                  </li>
                  <li>
                    <a href="#ab37bf30de" class="toc-h2 toc-link" data-title="">거래쌍 목록 조회하기</a>
                  </li>
                  <li>
                    <a href="#ticker" class="toc-h2 toc-link" data-title="ticker">Ticker 조회하기</a>
                  </li>
                  <li>
                    <a href="#orderbook" class="toc-h2 toc-link" data-title="orderbook">Orderbook 조회하기</a>
                  </li>
                  <li>
                    <a href="#ed00ab10dc" class="toc-h2 toc-link" data-title="">최근 체결 거래 조회하기</a>
                  </li>
                  <li>
                    <a href="#24" class="toc-h2 toc-link" data-title="24">최근 24시간 통계 조회하기</a>
                  </li>
                  <li>
                    <a href="#a1dac3e0a0" class="toc-h2 toc-link" data-title="">과거 기록 조회하기</a>
                  </li>
                  <li>
                    <a href="#24-2" class="toc-h2 toc-link" data-title="24">모든 거래쌍의 최근 24시간 통계 조회하기</a>
                  </li>
              </ul>
          </li>
          <li>
            <a href="#errors" class="toc-h1 toc-link" data-title="errors">Errors</a>
              <ul class="toc-list-h2">
                  <li>
                    <a href="#http-status" class="toc-h2 toc-link" data-title="http-status">HTTP Status (응답 코드)</a>
                  </li>
                  <li>
                    <a href="#gopax" class="toc-h2 toc-link" data-title="gopax">GOPAX 오류</a>
                  </li>
              </ul>
          </li>
      </div>
        <ul class="toc-footer">
            <li><a href='https://www.gopax.co.kr/account/' target='_blank'>API 키 받기</a></li>
            <li><a href='https://www.gopax.co.kr/' target='_blank'>GOPAX</a></li>
        </ul>
    </div>
    <div class="page-wrapper">
      <div class="dark-box"></div>
      <div class="content">
        <h1 id='fa255f0ccc'>소개</h1>
<p>Welcome to the GOPAX API!</p>

<p>REST API를 통해 GOPAX의 일부 기능을 이용하실 수 있도록 아래 문서를 공유합니다.</p>
<h2 id='rest-api'>REST API 주소</h2>
<p>고팍스의 REST API는 계정/주문 관리 및 공개 마켓 데이터에 대한 엔드포인트를 제공합니다.</p>

<p><code>https://api.gopax.co.kr</code></p>
<h2 id='api'>API 호출 횟수 제한</h2>
<ul>
<li>API 호출 횟수 제한을 초과하면 429 - 요청 한도 초과 상태코드가 반환됩니다.</li>
<li>인증이 필요한 API는 API Key당, 인증이 필요하지 않은 API는 IP당 호출 횟수가 제한됩니다.</li>
<li>최근 1초의 구간 안에서 최대 20번의 API 호출이 가능합니다.</li>
</ul>
<h1 id='ce7156229f'>인증</h1>
<p>Private API에 인증하기 위해, REST 요청에 항상 다음의 HTTP 헤더가 포함되어야 합니다.</p>

<ol>
<li>API-KEY: 발급받은 API 키</li>
<li>SIGNATURE: 메시지 서명 값 (<a href="#signature">* SIGNATURE 생성 과정</a>)</li>
<li>NONCE: 중복되지 않고 계속 증가하는 값 (통상적으로 timestamp)</li>
</ol>

<aside class="success">2개 이상의 API Key발급이 가능합니다.</aside>

<aside class="warning">같은 NONCE 값이 사용되면 서버에서 거부합니다.</aside>

<aside class="notice">HTTP 본문의 content-type은 application/json 으로 설정해야 합니다.</aside>
<h2 id='signature'>SIGNATURE 생성 과정</h2>
<blockquote>
<p>인증이 필요한 API는 아래 코드를 이용해주세요.</p>
</blockquote>
<pre class="highlight java tab-java"><code><span class="n">String</span> <span class="nf">generateSignature</span><span class="o">(</span><span class="n">String</span> <span class="n">secret</span><span class="o">,</span> <span class="n">String</span> <span class="n">method</span><span class="o">,</span> <span class="n">String</span> <span class="n">requestPath</span><span class="o">,</span>
  <span class="n">String</span> <span class="n">body</span><span class="o">)</span> <span class="kd">throws</span> <span class="n">NoSuchAlgorithmException</span><span class="o">,</span> <span class="n">InvalidKeyException</span> <span class="o">{</span>
  <span class="n">String</span> <span class="n">algorithm</span> <span class="o">=</span> <span class="s">"HmacSHA512"</span><span class="o">;</span>

  <span class="kt">long</span> <span class="n">nonce</span> <span class="o">=</span> <span class="n">System</span><span class="o">.</span><span class="na">currentTimeMillis</span><span class="o">()</span> <span class="o">/</span> <span class="mi">1000</span><span class="o">;</span>
  <span class="n">String</span> <span class="n">endPoint</span> <span class="o">=</span> <span class="n">requestPath</span><span class="o">.</span><span class="na">split</span><span class="o">(</span><span class="s">"\\?"</span><span class="o">)[</span><span class="mi">0</span><span class="o">];</span>

  <span class="n">String</span> <span class="n">what</span> <span class="o">=</span> <span class="n">nonce</span> <span class="o">+</span> <span class="n">method</span> <span class="o">+</span> <span class="n">endPoint</span> <span class="o">+</span> <span class="o">(</span><span class="n">body</span> <span class="o">==</span> <span class="kc">null</span> <span class="o">?</span> <span class="s">""</span> <span class="o">:</span> <span class="n">body</span><span class="o">);</span>

  <span class="n">Mac</span> <span class="n">sha512Hmac</span> <span class="o">=</span> <span class="n">Mac</span><span class="o">.</span><span class="na">getInstance</span><span class="o">(</span><span class="n">algorithm</span><span class="o">);</span>
  <span class="n">sha512Hmac</span><span class="o">.</span><span class="na">init</span><span class="o">(</span><span class="k">new</span> <span class="n">SecretKeySpec</span><span class="o">(</span><span class="n">Base64</span><span class="o">.</span><span class="na">decode</span><span class="o">(</span><span class="n">secret</span><span class="o">),</span> <span class="n">algorithm</span><span class="o">));</span>

  <span class="k">return</span> <span class="n">Base64</span><span class="o">.</span><span class="na">encodeAsString</span><span class="o">(</span><span class="n">sha512Hmac</span><span class="o">.</span><span class="na">doFinal</span><span class="o">(</span><span class="n">what</span><span class="o">.</span><span class="na">getBytes</span><span class="o">()));</span>
<span class="o">}</span>
</code></pre><pre class="highlight ruby tab-ruby"><code><span class="nb">require</span> <span class="s1">'json'</span>
<span class="nb">require</span> <span class="s1">'openssl'</span>
<span class="nb">require</span> <span class="s1">'Base64'</span>

<span class="k">def</span> <span class="nf">generateSignature</span><span class="p">(</span><span class="n">secret</span><span class="p">,</span> <span class="n">nonce</span><span class="p">,</span> <span class="nb">method</span><span class="p">,</span> <span class="n">path</span><span class="p">,</span> <span class="n">body</span><span class="o">=</span><span class="kp">nil</span><span class="p">)</span>
  <span class="n">_body</span> <span class="o">=</span> <span class="n">body</span> <span class="p">?</span> <span class="n">body</span><span class="p">.</span><span class="nf">to_json</span> <span class="p">:</span> <span class="s1">''</span>
  <span class="n">requestPath</span> <span class="o">=</span> <span class="n">path</span><span class="p">.</span><span class="nf">split</span><span class="p">(</span><span class="s1">'?'</span><span class="p">).</span><span class="nf">first</span>
  <span class="n">what</span>        <span class="o">=</span> <span class="n">nonce</span><span class="p">.</span><span class="nf">to_s</span> <span class="o">+</span> <span class="nb">method</span> <span class="o">+</span> <span class="n">requestPath</span> <span class="o">+</span> <span class="n">_body</span><span class="p">;</span>
  <span class="n">_secret</span>     <span class="o">=</span> <span class="no">Base64</span><span class="p">.</span><span class="nf">decode64</span><span class="p">(</span><span class="n">secret</span><span class="p">);</span>
  <span class="k">return</span> <span class="no">Base64</span><span class="p">.</span><span class="nf">strict_encode64</span><span class="p">(</span><span class="no">OpenSSL</span><span class="o">::</span><span class="no">HMAC</span><span class="p">.</span><span class="nf">digest</span><span class="p">(</span><span class="s1">'SHA512'</span><span class="p">,</span> <span class="n">_secret</span><span class="p">,</span> <span class="n">what</span><span class="p">))</span>
<span class="k">end</span>
</code></pre><pre class="highlight python tab-python"><code><span class="kn">import</span> <span class="nn">time</span><span class="p">,</span> <span class="n">base64</span><span class="p">,</span> <span class="n">hmac</span><span class="p">,</span> <span class="n">hashlib</span>

<span class="n">nonce</span> <span class="o">=</span> <span class="nb">str</span><span class="p">(</span><span class="n">time</span><span class="o">.</span><span class="n">time</span><span class="p">())</span>
<span class="n">method</span> <span class="o">=</span> <span class="s">'GET'</span>
<span class="n">request_path</span> <span class="o">=</span> <span class="s">'/balances'</span>

<span class="n">what</span> <span class="o">=</span> <span class="n">nonce</span> <span class="o">+</span> <span class="n">method</span> <span class="o">+</span> <span class="n">request_path</span> <span class="c"># + request_body</span>
<span class="n">key</span> <span class="o">=</span> <span class="n">base64</span><span class="o">.</span><span class="n">b64decode</span><span class="p">(</span><span class="n">secret</span><span class="p">)</span>
<span class="n">signature</span> <span class="o">=</span> <span class="n">hmac</span><span class="o">.</span><span class="n">new</span><span class="p">(</span><span class="n">key</span><span class="p">,</span> <span class="n">what</span><span class="p">,</span> <span class="n">hashlib</span><span class="o">.</span><span class="n">sha512</span><span class="p">)</span>
<span class="k">return</span> <span class="n">base64</span><span class="o">.</span><span class="n">b64encode</span><span class="p">(</span><span class="n">signature</span><span class="o">.</span><span class="n">digest</span><span class="p">())</span>
</code></pre><pre class="highlight php tab-php"><code>function generateSignature($secret, $nonce, $method, $path, $body = null)
{
  $_body = $body ? json_encode($body) : '';
  $tokenizedPath = explode('?', $path);
  $requestPath   = $tokenizedPath[0];
  $what          = $nonce . $method . $requestPath . $_body;
  $secret        = base64_decode($secret);
  return base64_encode(hash_hmac('sha512', $what, $secret, true));
}
</code></pre><pre class="highlight javascript tab-javascript"><code><span class="kr">const</span> <span class="nx">crypto</span> <span class="o">=</span> <span class="nx">require</span><span class="p">(</span><span class="s1">'crypto'</span><span class="p">);</span>

<span class="kr">const</span> <span class="nx">generateSignature</span> <span class="o">=</span> <span class="p">(</span><span class="nx">secret</span><span class="p">,</span> <span class="nx">nonce</span><span class="p">,</span> <span class="nx">method</span><span class="p">,</span> <span class="nx">path</span><span class="p">,</span> <span class="nx">body</span> <span class="o">=</span> <span class="kc">null</span><span class="p">)</span> <span class="o">=&gt;</span> <span class="p">{</span>
  <span class="kr">const</span> <span class="nx">requestPath</span> <span class="o">=</span> <span class="nx">path</span><span class="p">.</span><span class="nx">split</span><span class="p">(</span><span class="s1">'?'</span><span class="p">)[</span><span class="mi">0</span><span class="p">];</span>
  <span class="kr">const</span> <span class="nx">_body</span> <span class="o">=</span> <span class="nx">body</span> <span class="p">?</span> <span class="nx">JSON</span><span class="p">.</span><span class="nx">stringify</span><span class="p">(</span><span class="nx">body</span><span class="p">)</span> <span class="p">:</span> <span class="s1">''</span><span class="p">;</span>

  <span class="kr">const</span> <span class="nx">what</span> <span class="o">=</span> <span class="s2">`</span><span class="p">${</span><span class="nx">nonce</span><span class="p">}${</span><span class="nx">method</span><span class="p">}${</span><span class="nx">requestPath</span><span class="p">}${</span><span class="nx">_body</span><span class="p">}</span><span class="s2">`</span><span class="p">;</span>
  <span class="kr">const</span> <span class="nx">key</span> <span class="o">=</span> <span class="nx">Buffer</span><span class="p">(</span><span class="nx">secret</span><span class="p">,</span> <span class="s1">'base64'</span><span class="p">);</span>
  <span class="kr">const</span> <span class="nx">hmac</span> <span class="o">=</span> <span class="nx">crypto</span><span class="p">.</span><span class="nx">createHmac</span><span class="p">(</span><span class="s1">'sha512'</span><span class="p">,</span> <span class="nx">key</span><span class="p">);</span>
  <span class="k">return</span> <span class="nx">hmac</span><span class="p">.</span><span class="nx">update</span><span class="p">(</span><span class="nx">what</span><span class="p">).</span><span class="nx">digest</span><span class="p">(</span><span class="s1">'base64'</span><span class="p">);</span>
<span class="p">};</span>
</code></pre>
<ol>
<li>다음의 내용을 순서대로 문자열로 연결합니다.

<ol>
<li>헤더의 NONCE 값</li>
<li>HTTP Method(대문자로): &#39;GET&#39;, &#39;POST&#39;, &#39;DELETE&#39; 등</li>
<li>API 엔드포인트 경로 (예: &#39;/orders&#39;, &#39;/trading-pairs/ETH-KRW/book&#39;)</li>
<li>JSON 형식의 요청 변수 본문 (없을 경우 아무 문자열도 연결하지 마십시오)</li>
</ol></li>
<li>발급 받은 Secret Key를 base64로 디코딩합니다.</li>
<li>2.의 값을 Secret key를 사용하여 sha512 HMAC 으로 서명합니다.</li>
<li>3.의 값을 base64로 인코딩합니다.</li>
</ol>
<h2 id='http'>HTTP 헤더 예제</h2>
<p><code class="block">API-KEY: 128f0123-2a5d-48f5-8f19-e937f38f0a99<br />
SIGNATURE: gn2poOBVCAd5GLqXFAZGK9Pk4VD7+OaNtDIkFjejwIBjBm1X/DYPZVAP1rex6XqwH8vHt36ap26lTN85HVJz2g==<br />
NONCE: 1520994527165<br />
Content-Type: application/json
</code></p>

<aside class="notice">
위 예제는 테스트에 이용될 수 없습니다. <a href='https://www.gopax.co.kr/account/' target='_blank'>개인 API Key</a>를 통해서 생성해주세요.
</aside>
<h1 id='api-2'>인증이 필요한 API</h1><h2 id='44f0674afb'>잔액 조회하기</h2>
<blockquote>
<p>결과:</p>
</blockquote>
<pre class="highlight json tab-json"><code><span class="p">[</span><span class="w">
  </span><span class="p">{</span><span class="w">
    </span><span class="s2">"asset"</span><span class="p">:</span><span class="w"> </span><span class="s2">"KRW"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"avail"</span><span class="p">:</span><span class="w"> </span><span class="mf">9101080.53</span><span class="p">,</span><span class="w">
    </span><span class="s2">"hold"</span><span class="p">:</span><span class="w"> </span><span class="mi">0</span><span class="p">,</span><span class="w">
    </span><span class="s2">"pendingWithdrawal"</span><span class="p">:</span><span class="w"> </span><span class="mi">0</span><span class="w">
  </span><span class="p">},</span><span class="w"> </span><span class="p">{</span><span class="w">
    </span><span class="s2">"asset"</span><span class="p">:</span><span class="w"> </span><span class="s2">"ETH"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"avail"</span><span class="p">:</span><span class="w"> </span><span class="mi">0</span><span class="p">,</span><span class="w">
    </span><span class="s2">"hold"</span><span class="p">:</span><span class="w"> </span><span class="mi">0</span><span class="p">,</span><span class="w">
    </span><span class="s2">"pendingWithdrawal"</span><span class="p">:</span><span class="w"> </span><span class="mi">0</span><span class="w">
  </span><span class="p">},</span><span class="w"> </span><span class="p">{</span><span class="w">
    </span><span class="s2">"asset"</span><span class="p">:</span><span class="w"> </span><span class="s2">"BTC"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"avail"</span><span class="p">:</span><span class="w"> </span><span class="mf">0.42317058</span><span class="p">,</span><span class="w">
    </span><span class="s2">"hold"</span><span class="p">:</span><span class="w"> </span><span class="mi">0</span><span class="p">,</span><span class="w">
    </span><span class="s2">"pendingWithdrawal"</span><span class="p">:</span><span class="w"> </span><span class="mi">0</span><span class="w">
  </span><span class="p">},</span><span class="w"> </span><span class="p">{</span><span class="w">
    </span><span class="s2">"asset"</span><span class="p">:</span><span class="w"> </span><span class="s2">"BCH"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"avail"</span><span class="p">:</span><span class="w"> </span><span class="mi">0</span><span class="p">,</span><span class="w">
    </span><span class="s2">"hold"</span><span class="p">:</span><span class="w"> </span><span class="mi">0</span><span class="p">,</span><span class="w">
    </span><span class="s2">"pendingWithdrawal"</span><span class="p">:</span><span class="w"> </span><span class="mi">0</span><span class="w">
  </span><span class="p">}</span><span class="w">
</span><span class="p">]</span><span class="w">
</span></code></pre><h3 id='http-2'>HTTP 요청</h3>
<p><code>GET /balances</code></p>
<h3 id='cd5e8f5148'>결과값 설명</h3>
<p><code class="block" style="white-space: pre; color: grey; ">{
  &quot;asset&quot;: <i style="color: black;">&lt;Asset Name&gt;</i>,
  &quot;avail&quot;: <i style="color: black;">&lt;Avail&gt;</i>,
  &quot;hold&quot;: <i style="color: black;">&lt;Hold&gt;</i>,
  &quot;pendingWithdrawal&quot;: <i style="color: black;">&lt;Pending Withdrawal&gt;</i>
}, {
</code></p>

<table><thead>
<tr>
<th>값</th>
<th>설명</th>
</tr>
</thead><tbody>
<tr>
<td>Asset Name</td>
<td>자산 이름. <a href="#c8b9dcea10">자산 목록 조회하기</a>에서 전체 목록을 확인할 수 있습니다.</td>
</tr>
<tr>
<td>Avail</td>
<td>거래 가능 금액(수량)</td>
</tr>
<tr>
<td>Hold</td>
<td>미체결 금액(수량)</td>
</tr>
<tr>
<td>Pending Withdrawal</td>
<td>출금 중인 금액(수량)</td>
</tr>
</tbody></table>
<h2 id='105345e7b5'>자산 이름에 따라 잔액 조회하기</h2>
<blockquote>
<p>결과:</p>
</blockquote>
<pre class="highlight json tab-json"><code><span class="p">{</span><span class="w">
  </span><span class="s2">"asset"</span><span class="p">:</span><span class="w"> </span><span class="s2">"KRW"</span><span class="p">,</span><span class="w">
  </span><span class="s2">"avail"</span><span class="p">:</span><span class="w"> </span><span class="mf">9101080.53</span><span class="p">,</span><span class="w">
  </span><span class="s2">"hold"</span><span class="p">:</span><span class="w"> </span><span class="mi">0</span><span class="p">,</span><span class="w">
  </span><span class="s2">"pendingWithdrawal"</span><span class="p">:</span><span class="w"> </span><span class="mi">0</span><span class="w">
</span><span class="p">}</span><span class="w">
</span></code></pre><h3 id='http-3'>HTTP 요청</h3>
<p><code>GET /balances/&lt;Asset Name&gt;</code></p>
<h3 id='url'>URL 파라미터</h3>
<table><thead>
<tr>
<th>파라미터</th>
<th>설명</th>
</tr>
</thead><tbody>
<tr>
<td>Asset Name</td>
<td>자산 이름. <a href="#c8b9dcea10">자산 목록 조회하기</a>에서 전체 목록을 확인할 수 있습니다.</td>
</tr>
</tbody></table>
<h3 id='cd5e8f5148-2'>결과값 설명</h3>
<p><code class="block" style="white-space: pre; color: grey; ">{
  &quot;asset&quot;: <i style="color: black;">&lt;Asset Name&gt;</i>,
  &quot;avail&quot;: <i style="color: black;">&lt;Avail&gt;</i>,
  &quot;hold&quot;: <i style="color: black;">&lt;Hold&gt;</i>,
  &quot;pendingWithdrawal&quot;: <i style="color: black;">&lt;Pending Withdrawal&gt;</i>
}
</code></p>

<table><thead>
<tr>
<th>값</th>
<th>설명</th>
</tr>
</thead><tbody>
<tr>
<td>Asset Name</td>
<td>자산 이름. <a href="#c8b9dcea10">자산 목록 조회하기</a>에서 전체 목록을 확인할 수 있습니다.</td>
</tr>
<tr>
<td>Avail</td>
<td>거래 가능 금액(수량)</td>
</tr>
<tr>
<td>Hold</td>
<td>미체결 금액(수량)</td>
</tr>
<tr>
<td>Pending Withdrawal</td>
<td>출금 중인 금액(수량)</td>
</tr>
</tbody></table>
<h2 id='9a0aef758b'>주문 조회하기</h2>
<blockquote>
<p>결과:</p>
</blockquote>
<pre class="highlight json tab-json"><code><span class="p">[</span><span class="w">
  </span><span class="p">{</span><span class="w">
    </span><span class="s2">"id"</span><span class="p">:</span><span class="w"> </span><span class="s2">"23712"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"price"</span><span class="p">:</span><span class="w"> </span><span class="mi">101</span><span class="p">,</span><span class="w">
    </span><span class="s2">"amount"</span><span class="p">:</span><span class="w"> </span><span class="mi">100</span><span class="p">,</span><span class="w">
    </span><span class="s2">"tradingPairName"</span><span class="p">:</span><span class="w"> </span><span class="s2">"CND-KRW"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"side"</span><span class="p">:</span><span class="w"> </span><span class="s2">"sell"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"type"</span><span class="p">:</span><span class="w"> </span><span class="s2">"limit"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"createdAt"</span><span class="p">:</span><span class="w"> </span><span class="s2">"2018-01-08T12:44:03.000Z"</span><span class="w">
  </span><span class="p">},</span><span class="w"> </span><span class="p">{</span><span class="w">
    </span><span class="s2">"id"</span><span class="p">:</span><span class="w"> </span><span class="s2">"23916"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"price"</span><span class="p">:</span><span class="w"> </span><span class="mi">90</span><span class="p">,</span><span class="w">
    </span><span class="s2">"amount"</span><span class="p">:</span><span class="w"> </span><span class="mi">30</span><span class="p">,</span><span class="w">
    </span><span class="s2">"tradingPairName"</span><span class="p">:</span><span class="w"> </span><span class="s2">"CND-KRW"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"side"</span><span class="p">:</span><span class="w"> </span><span class="s2">"buy"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"type"</span><span class="p">:</span><span class="w"> </span><span class="s2">"limit"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"createdAt"</span><span class="p">:</span><span class="w"> </span><span class="s2">"2018-01-09T10:43:10.000Z"</span><span class="w">
  </span><span class="p">}</span><span class="w">
</span><span class="p">]</span><span class="w">
</span></code></pre><h3 id='http-4'>HTTP 요청</h3>
<p><code>GET /orders</code></p>
<h3 id='cd5e8f5148-3'>결과값 설명</h3>
<p><code class="block" style="white-space: pre; color: grey; ">{
  &quot;id&quot;: <i style="color: black;">&lt;ID&gt;</i>,
  &quot;price&quot;: <i style="color: black;">&lt;Price&gt;</i>,
  &quot;amount&quot;: <i style="color: black;">&lt;Amount&gt;</i>,
  &quot;tradingPairName&quot;: <i style="color: black;">&lt;Trading Pair&gt;</i>,
  &quot;side&quot;: <i style="color: black;">&lt;Side&gt;</i>,
  &quot;type&quot;: <i style="color: black;">&lt;Type&gt;</i>,
  &quot;createdAt&quot;: <i style="color: black;">&lt;Created At&gt;</i>
}, {
</code></p>

<table><thead>
<tr>
<th>값</th>
<th>설명</th>
</tr>
</thead><tbody>
<tr>
<td>ID</td>
<td>주문 고유번호</td>
</tr>
<tr>
<td>Price</td>
<td>주문 가격</td>
</tr>
<tr>
<td>Amount</td>
<td>주문 수량</td>
</tr>
<tr>
<td>Trading Pair</td>
<td>거래 쌍. <a href="#ab37bf30de">거래쌍 목록 조회하기</a>에서 전체 목록을 확인할 수 있습니다.</td>
</tr>
<tr>
<td>Side</td>
<td>주문 구분 (<code>buy</code>: 구매 또는 <code>sell</code>: 판매)</td>
</tr>
<tr>
<td>Type</td>
<td>주문 종류 (<code>limit</code>: 지정가 또는 <code>market</code>: 시장가)</td>
</tr>
<tr>
<td>Created At</td>
<td>주문 시각</td>
</tr>
</tbody></table>

<aside class="notice">ISO 8601 타임스탬프를 이용하고 있습니다</aside>
<h2 id='id'>주문 ID로 주문 조회하기</h2>
<blockquote>
<p>결과:</p>
</blockquote>
<pre class="highlight json tab-json"><code><span class="p">{</span><span class="w">
  </span><span class="s2">"id"</span><span class="p">:</span><span class="w"> </span><span class="s2">"23712"</span><span class="p">,</span><span class="w">
  </span><span class="s2">"status"</span><span class="p">:</span><span class="w"> </span><span class="s2">"placed"</span><span class="p">,</span><span class="w">
  </span><span class="s2">"side"</span><span class="p">:</span><span class="w"> </span><span class="s2">"sell"</span><span class="p">,</span><span class="w">
  </span><span class="s2">"type"</span><span class="p">:</span><span class="w"> </span><span class="s2">"limit"</span><span class="p">,</span><span class="w">
  </span><span class="s2">"price"</span><span class="p">:</span><span class="w"> </span><span class="mi">101</span><span class="p">,</span><span class="w">
  </span><span class="s2">"amount"</span><span class="p">:</span><span class="w"> </span><span class="mi">100</span><span class="p">,</span><span class="w">
  </span><span class="s2">"remaining"</span><span class="p">:</span><span class="w"> </span><span class="mi">100</span><span class="p">,</span><span class="w">
  </span><span class="s2">"tradingPairName"</span><span class="p">:</span><span class="w"> </span><span class="s2">"CND-KRW"</span><span class="p">,</span><span class="w">
  </span><span class="s2">"createdAt"</span><span class="p">:</span><span class="w"> </span><span class="s2">"2018-01-08T12:44:03.000Z"</span><span class="w">
</span><span class="p">}</span><span class="w">
</span></code></pre><h3 id='http-5'>HTTP 요청</h3>
<p><code>/orders/&lt;Order Id&gt;</code></p>
<h3 id='cd5e8f5148-4'>결과값 설명</h3>
<p><code class="block" style="white-space: pre; color: grey; ">{
  &quot;id&quot;: <i style="color: black;">&lt;ID&gt;</i>,
  &quot;status&quot;: <i style="color: black;">&lt;Status&gt;</i>,
  &quot;side&quot;: <i style="color: black;">&lt;Side&gt;</i>,
  &quot;type&quot;: <i style="color: black;">&lt;Type&gt;</i>,
  &quot;price&quot;: <i style="color: black;">&lt;Price&gt;</i>,
  &quot;amount&quot;: <i style="color: black;">&lt;Amount&gt;</i>,
  &quot;remaining&quot;: <i style="color: black;">&lt;Remaining&gt;</i>,
  &quot;tradingPairName&quot;: <i style="color: black;">&lt;Trading Pair&gt;</i>,
  &quot;createdAt&quot;: <i style="color: black;">&lt;Created At&gt;</i>
}
</code></p>

<table><thead>
<tr>
<th>값</th>
<th>설명</th>
</tr>
</thead><tbody>
<tr>
<td>ID</td>
<td>주문 고유번호</td>
</tr>
<tr>
<td>Status</td>
<td>상태 placed: 주문됨, cancelled: 취소됨, completed: 체결됨, updated: 부분 체결됨</td>
</tr>
<tr>
<td>Side</td>
<td>주문 구분 (<code>buy</code>: 구매 또는 <code>sell</code>: 판매)</td>
</tr>
<tr>
<td>Type</td>
<td>주문 종류 (<code>limit</code>: 지정가 또는 <code>market</code>: 시장가)</td>
</tr>
<tr>
<td>Price</td>
<td>주문 가격</td>
</tr>
<tr>
<td>Amount</td>
<td>주문 수량</td>
</tr>
<tr>
<td>Remaining</td>
<td>주문 잔량</td>
</tr>
<tr>
<td>Trading Pair</td>
<td>거래 쌍. <a href="#ab37bf30de">거래쌍 목록 조회하기</a>에서 전체 목록을 확인할 수 있습니다.</td>
</tr>
<tr>
<td>Created At</td>
<td>주문 시각</td>
</tr>
</tbody></table>

<aside class="notice">ISO 8601 타임스탬프를 이용하고 있습니다</aside>
<h2 id='6796537949'>주문 등록하기</h2>
<blockquote>
<p>결과:</p>
</blockquote>
<pre class="highlight json tab-json"><code><span class="p">{</span><span class="w">
  </span><span class="s2">"id"</span><span class="p">:</span><span class="w"> </span><span class="s2">"98723"</span><span class="p">,</span><span class="w">
  </span><span class="s2">"price"</span><span class="p">:</span><span class="w"> </span><span class="mi">750000</span><span class="p">,</span><span class="w">
  </span><span class="s2">"amount"</span><span class="p">:</span><span class="w"> </span><span class="mi">9</span><span class="p">,</span><span class="w">
  </span><span class="s2">"tradingPairName"</span><span class="p">:</span><span class="w"> </span><span class="s2">"ETH-KRW"</span><span class="p">,</span><span class="w">
  </span><span class="s2">"side"</span><span class="p">:</span><span class="w"> </span><span class="s2">"buy"</span><span class="p">,</span><span class="w">
  </span><span class="s2">"type"</span><span class="p">:</span><span class="w"> </span><span class="s2">"limit"</span><span class="p">,</span><span class="w">
  </span><span class="s2">"createdAt"</span><span class="p">:</span><span class="w"> </span><span class="s2">"2018-01-09T10:43:10.000Z"</span><span class="w">
</span><span class="p">}</span><span class="w">
</span></code></pre><h3 id='http-6'>HTTP 요청</h3>
<p><code>POST /orders</code></p>
<h3 id='9e02b329ac'>요청 본문 설명</h3>
<p><code class="block" style="white-space: pre; color: grey; ">{
  &quot;type&quot;: <i style="color: black;">&lt;Type&gt;</i>,
  &quot;side&quot;: <i style="color: black;">&lt;Side&gt;</i>,
  &quot;price&quot;: <i style="color: black;">&lt;Price&gt;</i>,
  &quot;amount&quot;: <i style="color: black;">&lt;Amount&gt;</i>,
  &quot;tradingPairName&quot;: <i style="color: black;">&lt;Trading Pair&gt;</i>
}
</code></p>

<table><thead>
<tr>
<th>값</th>
<th>설명</th>
</tr>
</thead><tbody>
<tr>
<td>Type</td>
<td>주문 종류 (<code>limit</code>: 지정가 또는 <code>market</code>: 시장가)</td>
</tr>
<tr>
<td>Side</td>
<td>주문 구분 (<code>buy</code>: 구매 또는 <code>sell</code>: 판매)</td>
</tr>
<tr>
<td>Price</td>
<td>주문 가격</td>
</tr>
<tr>
<td>Amount</td>
<td>주문 수량</td>
</tr>
<tr>
<td>Trading Pair</td>
<td>거래 쌍. <a href="#ab37bf30de">거래쌍 목록 조회하기</a>에서 전체 목록을 확인할 수 있습니다.</td>
</tr>
</tbody></table>

<blockquote>
<p>ETH-KRW를 지정가로 100만원에 ETH 10개 매수 예제</p>
</blockquote>
<pre class="highlight json tab-json"><code><span class="p">{</span><span class="w">
    </span><span class="s2">"type"</span><span class="p">:</span><span class="w"> </span><span class="s2">"limit"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"side"</span><span class="p">:</span><span class="w"> </span><span class="s2">"buy"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"price"</span><span class="p">:</span><span class="w"> </span><span class="mi">1000000</span><span class="p">,</span><span class="w">
    </span><span class="s2">"amount"</span><span class="p">:</span><span class="w"> </span><span class="mi">10</span><span class="p">,</span><span class="w">
    </span><span class="s2">"tradingPairName"</span><span class="p">:</span><span class="w"> </span><span class="s2">"ETH-KRW"</span><span class="w">
</span><span class="p">}</span><span class="w">
</span></code></pre>
<blockquote>
<p>ETH-KRW를 시장가로 ETH 10개 매도 예제</p>
</blockquote>
<pre class="highlight json tab-json"><code><span class="p">{</span><span class="w">
    </span><span class="s2">"type"</span><span class="p">:</span><span class="w"> </span><span class="s2">"market"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"side"</span><span class="p">:</span><span class="w"> </span><span class="s2">"sell"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"amount"</span><span class="p">:</span><span class="w"> </span><span class="mi">10</span><span class="p">,</span><span class="w">
    </span><span class="s2">"tradingPairName"</span><span class="p">:</span><span class="w"> </span><span class="s2">"ETH-KRW"</span><span class="w">
</span><span class="p">}</span><span class="w">
</span></code></pre>
<blockquote>
<p>ETH-KRW를 시장가로 1,000만원어치의 이더리움을 구매</p>
</blockquote>
<pre class="highlight json tab-json"><code><span class="p">{</span><span class="w">
  </span><span class="s2">"type"</span><span class="p">:</span><span class="w"> </span><span class="s2">"market"</span><span class="p">,</span><span class="w">
  </span><span class="s2">"side"</span><span class="p">:</span><span class="w"> </span><span class="s2">"buy"</span><span class="p">,</span><span class="w">
  </span><span class="s2">"amount"</span><span class="p">:</span><span class="w"> </span><span class="mi">10000000</span><span class="p">,</span><span class="w">
  </span><span class="s2">"tradingPairName"</span><span class="p">:</span><span class="w"> </span><span class="s2">"ETH-KRW"</span><span class="w">
</span><span class="p">}</span><span class="w">
</span></code></pre>
<aside class="warning">시장가 주문시 amount는 자신이 지불할 자산의 총량(ETH-KRW에서 매수의 경우 KRW, ETH-KRW에서 매도의 경우 ETH)입니다.</aside>
<h3 id='ca90ffae49'>최소 주문수량</h3>
<table><thead>
<tr>
<th>거래 쌍</th>
<th>최소 주문 수량</th>
<th>거래 쌍</th>
<th>최소 주문 수량</th>
</tr>
</thead><tbody>
<tr>
<td>ETH-KRW</td>
<td>0.001</td>
<td>CND-BTC</td>
<td>1</td>
</tr>
<tr>
<td>BTC-KRW</td>
<td>0.0001</td>
<td>SNT-BTC</td>
<td>1</td>
</tr>
<tr>
<td>BCH-KRW</td>
<td>0.001</td>
<td>ZRX-BTC</td>
<td>1</td>
</tr>
<tr>
<td>XLM-KRW</td>
<td>1</td>
<td>CND-KRW</td>
<td>1</td>
</tr>
<tr>
<td>ZEC-KRW</td>
<td>0.001</td>
<td>SNT-KRW</td>
<td>1</td>
</tr>
<tr>
<td>LTC-KRW</td>
<td>0.01</td>
<td>ZRX-KRW</td>
<td>1</td>
</tr>
<tr>
<td>ETH-BTC</td>
<td>0.001</td>
<td>EOS-KRW</td>
<td>1</td>
</tr>
<tr>
<td>BCH-BTC</td>
<td>0.0005</td>
<td>OMG-KRW</td>
<td>1</td>
</tr>
<tr>
<td>XLM-BTC</td>
<td>1</td>
<td>QTUM-KRW</td>
<td>0.05</td>
</tr>
<tr>
<td>ZEC-BTC</td>
<td>0.001</td>
<td>MOBI-KRW</td>
<td>1</td>
</tr>
<tr>
<td>LTC-BTC</td>
<td>0.005</td>
<td>STEEM-KRW</td>
<td>1</td>
</tr>
<tr>
<td>XLM-ETH</td>
<td>1</td>
<td>SBD-KRW</td>
<td>1</td>
</tr>
<tr>
<td>ENG-KRW</td>
<td>0.1</td>
<td>ELF-KRW</td>
<td>1</td>
</tr>
<tr>
<td>CVC-KRW</td>
<td>1</td>
<td>QASH-KRW</td>
<td>1</td>
</tr>
<tr>
<td>REQ-BTC</td>
<td>1</td>
<td>XRP-KRW</td>
<td>1</td>
</tr>
<tr>
<td>QASH-BTC</td>
<td>1</td>
<td></td>
<td></td>
</tr>
</tbody></table>
<h3 id='cd5e8f5148-5'>결과값 설명</h3>
<p><code class="block" style="white-space: pre; color: grey; ">{
  &quot;id&quot;: <i style="color: black;">&lt;ID&gt;</i>,
  &quot;price&quot;: <i style="color: black;">&lt;Price&gt;</i>,
  &quot;amount&quot;: <i style="color: black;">&lt;Amount&gt;</i>,
  &quot;tradingPairName&quot;: <i style="color: black;">&lt;Trading Pair&gt;</i>,
  &quot;side&quot;: <i style="color: black;">&lt;Side&gt;</i>,
  &quot;type&quot;: <i style="color: black;">&lt;Type&gt;</i>,
  &quot;createdAt&quot;: <i style="color: black;">&lt;Created At&gt;</i>
}</code></p>

<table><thead>
<tr>
<th>값</th>
<th>설명</th>
</tr>
</thead><tbody>
<tr>
<td>ID</td>
<td>주문 고유번호</td>
</tr>
<tr>
<td>Price</td>
<td>주문 가격</td>
</tr>
<tr>
<td>Amount</td>
<td>주문 수량</td>
</tr>
<tr>
<td>Trading Pair</td>
<td>거래 쌍. <a href="#ab37bf30de">거래쌍 목록 조회하기</a>에서 전체 목록을 확인할 수 있습니다.</td>
</tr>
<tr>
<td>Side</td>
<td>주문 구분 (<code>buy</code>: 구매 또는 <code>sell</code>: 판매)</td>
</tr>
<tr>
<td>Type</td>
<td>주문 종류 (<code>limit</code>: 지정가 또는 <code>market</code>: 시장가)</td>
</tr>
<tr>
<td>Created At</td>
<td>주문 시각</td>
</tr>
</tbody></table>

<aside class="notice">ISO 8601 타임스탬프를 이용하고 있습니다</aside>
<h2 id='id-2'>주문 ID로 주문 취소하기</h2>
<blockquote>
<p>결과:</p>
</blockquote>
<pre class="highlight json tab-json"><code><span class="p">{</span><span class="w">
</span><span class="p">}</span><span class="w">
</span></code></pre><h3 id='http-7'>HTTP 요청</h3>
<p><code>DELETE /orders/&lt;Order Id&gt;</code></p>
<h3 id='url-2'>URL 파라미터</h3>
<table><thead>
<tr>
<th>파라미터</th>
<th>설명</th>
</tr>
</thead><tbody>
<tr>
<td>Order Id</td>
<td>주문 고유번호</td>
</tr>
</tbody></table>
<h2 id='d603331cfe'>사용자 거래 기록 조회하기</h2>
<blockquote>
<p>결과:</p>
</blockquote>
<pre class="highlight json tab-json"><code><span class="p">[</span><span class="w">
  </span><span class="p">{</span><span class="w">
    </span><span class="s2">"id"</span><span class="p">:</span><span class="w"> </span><span class="mi">23152</span><span class="p">,</span><span class="w">
    </span><span class="s2">"orderId"</span><span class="p">:</span><span class="w"> </span><span class="mi">23712</span><span class="p">,</span><span class="w">
    </span><span class="s2">"baseAmount"</span><span class="p">:</span><span class="w"> </span><span class="mf">0.00968007</span><span class="p">,</span><span class="w">
    </span><span class="s2">"quoteAmount"</span><span class="p">:</span><span class="w"> </span><span class="mf">99999.963135</span><span class="p">,</span><span class="w">
    </span><span class="s2">"fee"</span><span class="p">:</span><span class="w"> </span><span class="mi">0</span><span class="p">,</span><span class="w">
    </span><span class="s2">"price"</span><span class="p">:</span><span class="w"> </span><span class="mi">10330500</span><span class="p">,</span><span class="w">
    </span><span class="s2">"timestamp"</span><span class="p">:</span><span class="w"> </span><span class="s2">"2018-03-10T16:07:32.000Z"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"side"</span><span class="p">:</span><span class="w"> </span><span class="s2">"buy"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"tradingPairName"</span><span class="p">:</span><span class="w"> </span><span class="s2">"BTC-KRW"</span><span class="w">
  </span><span class="p">},</span><span class="w"> </span><span class="p">{</span><span class="w">
    </span><span class="s2">"id"</span><span class="p">:</span><span class="w"> </span><span class="mi">23302</span><span class="p">,</span><span class="w">
    </span><span class="s2">"orderId"</span><span class="p">:</span><span class="w"> </span><span class="mi">23916</span><span class="p">,</span><span class="w">
    </span><span class="s2">"baseAmount"</span><span class="p">:</span><span class="w"> </span><span class="mf">0.00149051</span><span class="p">,</span><span class="w">
    </span><span class="s2">"quoteAmount"</span><span class="p">:</span><span class="w"> </span><span class="mf">15399.94932</span><span class="p">,</span><span class="w">
    </span><span class="s2">"fee"</span><span class="p">:</span><span class="w"> </span><span class="mi">0</span><span class="p">,</span><span class="w">
    </span><span class="s2">"price"</span><span class="p">:</span><span class="w"> </span><span class="mi">10332000</span><span class="p">,</span><span class="w">
    </span><span class="s2">"timestamp"</span><span class="p">:</span><span class="w"> </span><span class="s2">"2018-03-10T16:03:54.000Z"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"side"</span><span class="p">:</span><span class="w"> </span><span class="s2">"buy"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"tradingPairName"</span><span class="p">:</span><span class="w"> </span><span class="s2">"BTC-KRW"</span><span class="w">
  </span><span class="p">}</span><span class="w">
</span><span class="p">]</span><span class="w">
</span></code></pre><h3 id='http-8'>HTTP 요청</h3>
<p><code>GET /trades</code></p>
<h3 id='cd5e8f5148-6'>결과값 설명</h3>
<p><code class="block" style="white-space: pre; color: grey;">{
  &quot;id&quot;: <i style="color: black;">&lt;ID&gt;</i>,
  &quot;orderId&quot;: <i style="color: black;">&lt;Order ID&gt;</i>,
  &quot;baseAmount&quot;: <i style="color: black;">&lt;Base Amount&gt;</i>,
  &quot;quoteAmount&quot;: <i style="color: black;">&lt;Quote Amount&gt;</i>,
  &quot;fee&quot;: <i style="color: black;">&lt;Fee&gt;</i>,
  &quot;price&quot;: <i style="color: black;">&lt;Price&gt;</i>,
  &quot;timestamp&quot;: <i style="color: black;">&lt;Timestamp&gt;</i>,
  &quot;side&quot;: <i style="color: black;">&lt;Side&gt;</i>,
  &quot;tradingPairName&quot;: <i style="color: black;">&lt;Trading Pair&gt;</i>
}, {
</code></p>

<table><thead>
<tr>
<th>값</th>
<th>설명</th>
</tr>
</thead><tbody>
<tr>
<td>ID</td>
<td>거래 고유번호</td>
</tr>
<tr>
<td>Order ID</td>
<td>주문 고유번호</td>
</tr>
<tr>
<td>Base Amount</td>
<td>거래 수량 (구매시 Fee 가 포함된 수량)</td>
</tr>
<tr>
<td>Quote Amount</td>
<td>거래 수량 * 주문 가격 (판매시 Fee 가 포함된 금액)</td>
</tr>
<tr>
<td>Fee</td>
<td>거래 수수료 <a href="https://www.gopax.co.kr/feeinfo">수수료테이블 링크</a></td>
</tr>
<tr>
<td>Price</td>
<td>주문 가격</td>
</tr>
<tr>
<td>Timestamp</td>
<td>거래 체결 시간</td>
</tr>
<tr>
<td>Side</td>
<td>거래 체결 종류 (<code>buy</code> 또는 <code>sell</code>)</td>
</tr>
<tr>
<td>Trading Pair</td>
<td>거래 쌍. <a href="#ab37bf30de">거래쌍 목록 조회하기</a>에서 전체 목록을 확인할 수 있습니다.</td>
</tr>
</tbody></table>

<aside class="notice">ISO 8601 타임스탬프를 이용하고 있습니다</aside>
<h1 id='api-3'>인증이 필요하지 않은 API</h1><h2 id='c8b9dcea10'>자산 목록 조회하기</h2>
<blockquote>
<p>결과:</p>
</blockquote>
<pre class="highlight json tab-json"><code><span class="p">[</span><span class="w">
  </span><span class="p">{</span><span class="w">
    </span><span class="s2">"id"</span><span class="p">:</span><span class="w"> </span><span class="s2">"KRW"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"name"</span><span class="p">:</span><span class="w"> </span><span class="s2">"대한민국 원"</span><span class="w">
  </span><span class="p">},</span><span class="w"> </span><span class="p">{</span><span class="w">
    </span><span class="s2">"id"</span><span class="p">:</span><span class="w"> </span><span class="s2">"ETH"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"name"</span><span class="p">:</span><span class="w"> </span><span class="s2">"이더리움"</span><span class="w">
  </span><span class="p">},</span><span class="w"> </span><span class="p">{</span><span class="w">
    </span><span class="s2">"id"</span><span class="p">:</span><span class="w"> </span><span class="s2">"BTC"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"name"</span><span class="p">:</span><span class="w"> </span><span class="s2">"비트코인"</span><span class="w">
  </span><span class="p">}</span><span class="w">
</span><span class="p">]</span><span class="w">
</span></code></pre>
<p>GOPAX 지갑에서 취급하는 모든 자산의 목록을 조회할 수 있습니다.</p>
<h3 id='http-9'>HTTP 요청</h3>
<p><code>GET /assets</code></p>
<h2 id='ab37bf30de'>거래쌍 목록 조회하기</h2>
<blockquote>
<p>결과:</p>
</blockquote>
<pre class="highlight json tab-json"><code><span class="p">[</span><span class="w">
  </span><span class="p">{</span><span class="w">
    </span><span class="s2">"name"</span><span class="p">:</span><span class="w"> </span><span class="s2">"ETH-KRW"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"baseAsset"</span><span class="p">:</span><span class="w"> </span><span class="s2">"ETH"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"quoteAsset"</span><span class="p">:</span><span class="w"> </span><span class="s2">"KRW"</span><span class="w">
  </span><span class="p">},</span><span class="w"> </span><span class="p">{</span><span class="w">
    </span><span class="s2">"name"</span><span class="p">:</span><span class="w"> </span><span class="s2">"BTC-KRW"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"baseAsset"</span><span class="p">:</span><span class="w"> </span><span class="s2">"BTC"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"quoteAsset"</span><span class="p">:</span><span class="w"> </span><span class="s2">"KRW"</span><span class="w">
  </span><span class="p">},</span><span class="w"> </span><span class="p">{</span><span class="w">
    </span><span class="s2">"name"</span><span class="p">:</span><span class="w"> </span><span class="s2">"BCH-KRW"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"baseAsset"</span><span class="p">:</span><span class="w"> </span><span class="s2">"BCH"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"quoteAsset"</span><span class="p">:</span><span class="w"> </span><span class="s2">"KRW"</span><span class="w">
  </span><span class="p">}</span><span class="w">
</span><span class="p">]</span><span class="w">
</span></code></pre><h3 id='http-10'>HTTP 요청</h3>
<p><code>GET /trading-pairs</code></p>
<h2 id='ticker'>Ticker 조회하기</h2>
<blockquote>
<p>결과:</p>
</blockquote>
<pre class="highlight json tab-json"><code><span class="p">{</span><span class="w">
  </span><span class="s2">"price"</span><span class="p">:</span><span class="w"> </span><span class="mi">10194500</span><span class="p">,</span><span class="w">
  </span><span class="s2">"ask"</span><span class="p">:</span><span class="w"> </span><span class="mi">10195000</span><span class="p">,</span><span class="w">
  </span><span class="s2">"bid"</span><span class="p">:</span><span class="w"> </span><span class="mi">10184500</span><span class="p">,</span><span class="w">
  </span><span class="s2">"volume"</span><span class="p">:</span><span class="w"> </span><span class="mf">1752.05558316</span><span class="p">,</span><span class="w">
  </span><span class="s2">"time"</span><span class="p">:</span><span class="w"> </span><span class="s2">"2018-03-14T03:50:41.184Z"</span><span class="w">
</span><span class="p">}</span><span class="w">
</span></code></pre><h3 id='http-11'>HTTP 요청</h3>
<p><code>GET /trading-pairs/&lt;Trading Pair&gt;/ticker</code></p>
<h3 id='url-3'>URL 파라미터</h3>
<table><thead>
<tr>
<th>파라미터</th>
<th>설명</th>
</tr>
</thead><tbody>
<tr>
<td>Trading Pair</td>
<td>거래 쌍. <a href="#ab37bf30de">거래쌍 목록 조회하기</a>에서 전체 목록을 확인할 수 있습니다.</td>
</tr>
</tbody></table>

<aside class="notice">ISO 8601 타임스탬프를 이용하고 있습니다</aside>
<h2 id='orderbook'>Orderbook 조회하기</h2>
<blockquote>
<p>결과:</p>
</blockquote>
<pre class="highlight json tab-json"><code><span class="p">{</span><span class="w">
  </span><span class="s2">"bid"</span><span class="p">:</span><span class="w"> </span><span class="p">[</span><span class="w">
    </span><span class="p">[</span><span class="s2">"481172"</span><span class="p">,</span><span class="w"> </span><span class="mi">10163500</span><span class="p">,</span><span class="w"> </span><span class="mf">0.0001</span><span class="p">]</span><span class="w">
  </span><span class="p">],</span><span class="w">
  </span><span class="s2">"ask"</span><span class="p">:</span><span class="w"> </span><span class="p">[</span><span class="w">
    </span><span class="p">[</span><span class="s2">"481205"</span><span class="p">,</span><span class="w"> </span><span class="mi">10164000</span><span class="p">,</span><span class="w"> </span><span class="mf">3.10024529</span><span class="p">]</span><span class="w">
  </span><span class="p">]</span><span class="w">
</span><span class="p">}</span><span class="w">
</span></code></pre><h3 id='http-12'>HTTP 요청</h3>
<p><code>GET /trading-pairs/&lt;Trading Pair&gt;/book</code></p>
<h3 id='url-4'>URL 파라미터</h3>
<table><thead>
<tr>
<th>파라미터</th>
<th>설명</th>
</tr>
</thead><tbody>
<tr>
<td>Trading Pair</td>
<td>거래 쌍. <a href="#ab37bf30de">거래쌍 목록 조회하기</a>에서 전체 목록을 확인할 수 있습니다.</td>
</tr>
</tbody></table>
<h3 id='query'>Query 파라미터</h3>
<table><thead>
<tr>
<th>파라미터</th>
<th>필수 여부</th>
<th>설명</th>
</tr>
</thead><tbody>
<tr>
<td>level</td>
<td>선택</td>
<td>호가창의 상세정보 수준 <br /><br />1 = 매수호가 및 매도호가<br />2 = 매수 및 매도 주문 각 50개<br />기타 = 호가창 전체</td>
</tr>
</tbody></table>
<h3 id='cd5e8f5148-7'>결과값 설명</h3>
<p><code class="block" style="white-space: pre; color: grey; ">{
  &quot;bid&quot;: [
    <i style="color: black;">[&lt;ID&gt;, &lt;가격&gt;, &lt;수량&gt;]</i>
  ],
  &quot;ask&quot;: [
    [&quot;481205&quot;, 10164000, 3.10024529]
  ]
}
</code></p>

<table><thead>
<tr>
<th>값</th>
<th>설명</th>
</tr>
</thead><tbody>
<tr>
<td>ID</td>
<td>호가에 부여되는 고유번호 (더이상 사용되지 않습니다)</td>
</tr>
<tr>
<td>가격</td>
<td>호가에 해당하는 가격</td>
</tr>
<tr>
<td>수량</td>
<td>호가에 해당하는 수량</td>
</tr>
</tbody></table>
<h2 id='ed00ab10dc'>최근 체결 거래 조회하기</h2>
<blockquote>
<p>결과:</p>
</blockquote>
<pre class="highlight json tab-json"><code><span class="p">[</span><span class="w">
  </span><span class="p">{</span><span class="w">
    </span><span class="s2">"time"</span><span class="p">:</span><span class="w"> </span><span class="s2">"2018-03-14T04:01:17.000Z"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"date"</span><span class="p">:</span><span class="w"> </span><span class="mi">1521000077</span><span class="p">,</span><span class="w">
    </span><span class="s2">"id"</span><span class="p">:</span><span class="w"> </span><span class="mi">6436174</span><span class="p">,</span><span class="w">
    </span><span class="s2">"price"</span><span class="p">:</span><span class="w"> </span><span class="mi">10163000</span><span class="p">,</span><span class="w">
    </span><span class="s2">"amount"</span><span class="p">:</span><span class="w"> </span><span class="mf">0.38115097</span><span class="p">,</span><span class="w">
    </span><span class="s2">"side"</span><span class="p">:</span><span class="w"> </span><span class="s2">"sell"</span><span class="w">
  </span><span class="p">},</span><span class="w"> </span><span class="p">{</span><span class="w">
    </span><span class="s2">"time"</span><span class="p">:</span><span class="w"> </span><span class="s2">"2018-03-14T04:01:17.000Z"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"date"</span><span class="p">:</span><span class="w"> </span><span class="mi">1521000077</span><span class="p">,</span><span class="w">
    </span><span class="s2">"id"</span><span class="p">:</span><span class="w"> </span><span class="mi">6436173</span><span class="p">,</span><span class="w">
    </span><span class="s2">"price"</span><span class="p">:</span><span class="w"> </span><span class="mi">10164500</span><span class="p">,</span><span class="w">
    </span><span class="s2">"amount"</span><span class="p">:</span><span class="w"> </span><span class="mf">0.12818829</span><span class="p">,</span><span class="w">
    </span><span class="s2">"side"</span><span class="p">:</span><span class="w"> </span><span class="s2">"sell"</span><span class="w">
  </span><span class="p">},</span><span class="w"> </span><span class="p">{</span><span class="w">
    </span><span class="s2">"time"</span><span class="p">:</span><span class="w"> </span><span class="s2">"2018-03-14T04:01:11.000Z"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"date"</span><span class="p">:</span><span class="w"> </span><span class="mi">1521000071</span><span class="p">,</span><span class="w">
    </span><span class="s2">"id"</span><span class="p">:</span><span class="w"> </span><span class="mi">6436171</span><span class="p">,</span><span class="w">
    </span><span class="s2">"price"</span><span class="p">:</span><span class="w"> </span><span class="mi">10163000</span><span class="p">,</span><span class="w">
    </span><span class="s2">"amount"</span><span class="p">:</span><span class="w"> </span><span class="mf">0.098</span><span class="p">,</span><span class="w">
    </span><span class="s2">"side"</span><span class="p">:</span><span class="w"> </span><span class="s2">"sell"</span><span class="w">
  </span><span class="p">}</span><span class="w">
</span><span class="p">]</span><span class="w">
</span></code></pre><h3 id='http-13'>HTTP 요청</h3>
<p><code>GET /trading-pairs/&lt;Trading Pair&gt;/trades</code></p>
<h3 id='url-5'>URL 파라미터</h3>
<table><thead>
<tr>
<th>파라미터</th>
<th>설명</th>
</tr>
</thead><tbody>
<tr>
<td>Trading Pair</td>
<td>거래 쌍. <a href="#ab37bf30de">거래쌍 목록 조회하기</a>에서 전체 목록을 확인할 수 있습니다.</td>
</tr>
</tbody></table>
<h3 id='query-2'>Query 파라미터</h3>
<table><thead>
<tr>
<th>파라미터</th>
<th>필수 여부</th>
<th>설명</th>
</tr>
</thead><tbody>
<tr>
<td>limit</td>
<td>선택</td>
<td>반환되는 항목의 갯수 (최대 100)</td>
</tr>
<tr>
<td>pastmax</td>
<td>선택</td>
<td>이 ID보다 오래된 데이터를 제외함</td>
</tr>
<tr>
<td>latestmin</td>
<td>선택</td>
<td>이 ID보다 새로운 최신 데이터를 가져옴</td>
</tr>
<tr>
<td>after</td>
<td>선택</td>
<td>이 타임스탬프 이후의 데이터를 제외함 (ms 단위)</td>
</tr>
<tr>
<td>before</td>
<td>선택</td>
<td>이 타임스탬프 이전의 데이터를 제외함 (ms 단위)</td>
</tr>
</tbody></table>
<h3 id='cd5e8f5148-8'>결과값 설명</h3>
<p><code class="block" style="white-space: pre; color: grey; ">{
  &quot;time&quot;: <i style="color: black;">&lt;Time&gt;</i>,
  &quot;id&quot;: <i style="color: black;">&lt;ID&gt;</i>,
  &quot;price&quot;: <i style="color: black;">&lt;Price&gt;</i>,
  &quot;amount&quot;: <i style="color: black;">&lt;Amount&gt;</i>,
  &quot;side&quot;: <i style="color: black;">&lt;Side&gt;</i>,
}, {
</code></p>

<table><thead>
<tr>
<th>값</th>
<th>설명</th>
</tr>
</thead><tbody>
<tr>
<td>Time</td>
<td>거래 체결 시각</td>
</tr>
<tr>
<td>ID</td>
<td>거래 체결 고유번호</td>
</tr>
<tr>
<td>Price</td>
<td>거래 체결 가격</td>
</tr>
<tr>
<td>Amount</td>
<td>거래 체결 수량</td>
</tr>
<tr>
<td>Side</td>
<td>거래 체결 종류 (<code>buy</code> 또는 <code>sell</code>)</td>
</tr>
</tbody></table>

<aside class="notice">ISO 8601 타임스탬프를 이용하고 있습니다</aside>
<h2 id='24'>최근 24시간 통계 조회하기</h2>
<blockquote>
<p>결과:</p>
</blockquote>
<pre class="highlight json tab-json"><code><span class="p">{</span><span class="w">
  </span><span class="s2">"open"</span><span class="p">:</span><span class="w"> </span><span class="mi">10297000</span><span class="p">,</span><span class="w">
  </span><span class="s2">"high"</span><span class="p">:</span><span class="w"> </span><span class="mi">10362500</span><span class="p">,</span><span class="w">
  </span><span class="s2">"low"</span><span class="p">:</span><span class="w"> </span><span class="mi">9901000</span><span class="p">,</span><span class="w">
  </span><span class="s2">"close"</span><span class="p">:</span><span class="w"> </span><span class="mi">10089500</span><span class="p">,</span><span class="w">
  </span><span class="s2">"volume"</span><span class="p">:</span><span class="w"> </span><span class="mf">1700.84866009</span><span class="p">,</span><span class="w">
  </span><span class="s2">"time"</span><span class="p">:</span><span class="w"> </span><span class="s2">"2018-03-14T05:02:37.337Z"</span><span class="w">
</span><span class="p">}</span><span class="w">
</span></code></pre><h3 id='http-14'>HTTP 요청</h3>
<p><code>GET /trading-pairs/&lt;Trading Pair&gt;/stats</code></p>
<h3 id='cd5e8f5148-9'>결과값 설명</h3>
<p><code class="block" style="white-space: pre; color: grey; ">{
  &quot;open&quot;: <i style="color: black;">&lt;Open&gt;</i>,
  &quot;high&quot;: <i style="color: black;">&lt;High&gt;</i>,
  &quot;low&quot;: <i style="color: black;">&lt;Low&gt;</i>,
  &quot;close&quot;: <i style="color: black;">&lt;Close&gt;</i>,
  &quot;volume&quot;: <i style="color: black;">&lt;Volume&gt;</i>,
  &quot;time&quot;: <i style="color: black;">&lt;Time&gt;</i>,
}
</code></p>

<table><thead>
<tr>
<th>값</th>
<th>설명</th>
</tr>
</thead><tbody>
<tr>
<td>Open</td>
<td>24시간 전의 가격</td>
</tr>
<tr>
<td>High</td>
<td>24시간 동안의 최고가</td>
</tr>
<tr>
<td>Low</td>
<td>24시간 동안의 최저가</td>
</tr>
<tr>
<td>Close</td>
<td>현재가 (1분마다 갱신)</td>
</tr>
<tr>
<td>Volume</td>
<td>24시간 동안의 거래량</td>
</tr>
<tr>
<td>Time</td>
<td>최근 데이터 갱신 시각</td>
</tr>
</tbody></table>

<aside class="notice">ISO 8601 타임스탬프를 이용하고 있습니다</aside>
<h2 id='a1dac3e0a0'>과거 기록 조회하기</h2>
<blockquote>
<p>결과:</p>
</blockquote>
<pre class="highlight json tab-json"><code><span class="p">[</span><span class="w">
  </span><span class="p">[</span><span class="w">
    </span><span class="mi">1521004020000</span><span class="p">,</span><span class="w">
    </span><span class="mi">10081000</span><span class="p">,</span><span class="w">
    </span><span class="mi">10081000</span><span class="p">,</span><span class="w">
    </span><span class="mi">10081000</span><span class="p">,</span><span class="w">
    </span><span class="mi">10081000</span><span class="p">,</span><span class="w">
    </span><span class="mf">0.0398393</span><span class="w">
  </span><span class="p">],</span><span class="w">
  </span><span class="p">[</span><span class="w">
    </span><span class="mi">1521004080000</span><span class="p">,</span><span class="w">
    </span><span class="mi">10081000</span><span class="p">,</span><span class="w">
    </span><span class="mi">10081000</span><span class="p">,</span><span class="w">
    </span><span class="mi">10081000</span><span class="p">,</span><span class="w">
    </span><span class="mi">10081000</span><span class="p">,</span><span class="w">
    </span><span class="mf">0.01</span><span class="w">
  </span><span class="p">]</span><span class="w">
</span><span class="p">]</span><span class="w">
</span></code></pre><h3 id='http-15'>HTTP 요청</h3>
<p><code>GET /trading-pairs/&lt;Trading Pair&gt;/candles?start=&lt;Start&gt;&amp;end=&lt;End&gt;&amp;interval=&lt;Interval&gt;</code></p>
<h3 id='url-6'>URL 파라미터</h3>
<table><thead>
<tr>
<th>파라미터</th>
<th>설명</th>
</tr>
</thead><tbody>
<tr>
<td>Trading Pair</td>
<td>거래 쌍. <a href="#ab37bf30de">거래쌍 목록 조회하기</a>에서 전체 목록을 확인할 수 있습니다.</td>
</tr>
</tbody></table>
<h3 id='query-3'>Query 파라미터</h3>
<table><thead>
<tr>
<th>파라미터</th>
<th>필수 여부</th>
<th>설명</th>
</tr>
</thead><tbody>
<tr>
<td>Start</td>
<td>필수</td>
<td>시작 시점 Timestamp (ms 단위)</td>
</tr>
<tr>
<td>End</td>
<td>필수</td>
<td>종료 시점 Timestamp (ms 단위)</td>
</tr>
<tr>
<td>Interval</td>
<td>필수</td>
<td>희망하는 시간 간격 (분 단위, 1/5/30/1440)</td>
</tr>
</tbody></table>
<h3 id='cd5e8f5148-10'>결과값 설명</h3>
<p><code class="block" style="white-space: pre; color: grey; ">[
  [
    <i style="color: black;">&lt;Time&gt;</i>,
    <i style="color: black;">&lt;Low&gt;</i>,
    <i style="color: black;">&lt;High&gt;</i>,
    <i style="color: black;">&lt;Open&gt;</i>,
    <i style="color: black;">&lt;Close&gt;</i>,
    <i style="color: black;">&lt;Volume&gt;</i>
  ],
  [
    1521004080000,
    10081000,
    10081000,
    10081000,
    10081000,
    0.01
  ]
]
</code></p>

<table><thead>
<tr>
<th>값</th>
<th>설명</th>
</tr>
</thead><tbody>
<tr>
<td>Time</td>
<td>최근 데이터 갱신 시각</td>
</tr>
<tr>
<td>Low</td>
<td>24시간 동안의 최저가</td>
</tr>
<tr>
<td>High</td>
<td>24시간 동안의 최고가</td>
</tr>
<tr>
<td>Open</td>
<td>24시간 전의 가격</td>
</tr>
<tr>
<td>Close</td>
<td>현재가 (1분마다 갱신)</td>
</tr>
<tr>
<td>Volume</td>
<td>24시간 동안의 거래량</td>
</tr>
</tbody></table>
<h2 id='24-2'>모든 거래쌍의 최근 24시간 통계 조회하기</h2>
<blockquote>
<p>결과:</p>
</blockquote>
<pre class="highlight json tab-json"><code><span class="p">[</span><span class="w">
  </span><span class="p">{</span><span class="w">
    </span><span class="s2">"name"</span><span class="p">:</span><span class="w"> </span><span class="s2">"ETH-KRW"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"open"</span><span class="p">:</span><span class="w"> </span><span class="mi">780000</span><span class="p">,</span><span class="w">
    </span><span class="s2">"high"</span><span class="p">:</span><span class="w"> </span><span class="mi">784000</span><span class="p">,</span><span class="w">
    </span><span class="s2">"low"</span><span class="p">:</span><span class="w"> </span><span class="mi">756000</span><span class="p">,</span><span class="w">
    </span><span class="s2">"close"</span><span class="p">:</span><span class="w"> </span><span class="mi">763500</span><span class="p">,</span><span class="w">
    </span><span class="s2">"volume"</span><span class="p">:</span><span class="w"> </span><span class="mf">1602.93236136</span><span class="p">,</span><span class="w">
    </span><span class="s2">"time"</span><span class="p">:</span><span class="w"> </span><span class="s2">"2018-03-14T05:13:08.364Z"</span><span class="w">
  </span><span class="p">},</span><span class="w"> </span><span class="p">{</span><span class="w">
    </span><span class="s2">"name"</span><span class="p">:</span><span class="w"> </span><span class="s2">"BTC-KRW"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"open"</span><span class="p">:</span><span class="w"> </span><span class="mi">10308000</span><span class="p">,</span><span class="w">
    </span><span class="s2">"high"</span><span class="p">:</span><span class="w"> </span><span class="mi">10362500</span><span class="p">,</span><span class="w">
    </span><span class="s2">"low"</span><span class="p">:</span><span class="w"> </span><span class="mi">9901000</span><span class="p">,</span><span class="w">
    </span><span class="s2">"close"</span><span class="p">:</span><span class="w"> </span><span class="mi">10074000</span><span class="p">,</span><span class="w">
    </span><span class="s2">"volume"</span><span class="p">:</span><span class="w"> </span><span class="mf">1687.88476801</span><span class="p">,</span><span class="w">
    </span><span class="s2">"time"</span><span class="p">:</span><span class="w"> </span><span class="s2">"2018-03-14T05:12:08.245Z"</span><span class="w">
  </span><span class="p">},</span><span class="w"> </span><span class="p">{</span><span class="w">
    </span><span class="s2">"name"</span><span class="p">:</span><span class="w"> </span><span class="s2">"BCH-KRW"</span><span class="p">,</span><span class="w">
    </span><span class="s2">"open"</span><span class="p">:</span><span class="w"> </span><span class="mi">1234000</span><span class="p">,</span><span class="w">
    </span><span class="s2">"high"</span><span class="p">:</span><span class="w"> </span><span class="mi">1234000</span><span class="p">,</span><span class="w">
    </span><span class="s2">"low"</span><span class="p">:</span><span class="w"> </span><span class="mi">1120000</span><span class="p">,</span><span class="w">
    </span><span class="s2">"close"</span><span class="p">:</span><span class="w"> </span><span class="mi">1149500</span><span class="p">,</span><span class="w">
    </span><span class="s2">"volume"</span><span class="p">:</span><span class="w"> </span><span class="mf">35.12077207</span><span class="p">,</span><span class="w">
    </span><span class="s2">"time"</span><span class="p">:</span><span class="w"> </span><span class="s2">"2018-03-14T04:40:06.535Z"</span><span class="w">
  </span><span class="p">}</span><span class="w">
</span><span class="p">]</span><span class="w">
</span></code></pre><h3 id='http-16'>HTTP 요청</h3>
<p><code>GET /trading-pairs/stats</code></p>
<h3 id='cd5e8f5148-11'>결과값 설명</h3>
<p><code class="block" style="white-space: pre; color: grey; ">  {
  &quot;name&quot;: <i style="color: black;">&lt;Trading Pair&gt;</i>,
  &quot;open&quot;: <i style="color: black;">&lt;Open&gt;</i>,
  &quot;high&quot;: <i style="color: black;">&lt;High&gt;</i>,
  &quot;low&quot;: <i style="color: black;">&lt;Low&gt;</i>,
  &quot;close&quot;: <i style="color: black;">&lt;Close&gt;</i>,
  &quot;volume&quot;: <i style="color: black;">&lt;Volume&gt;</i>,
  &quot;time&quot;: <i style="color: black;">&lt;Time&gt;</i>
}, {
</code></p>

<table><thead>
<tr>
<th>값</th>
<th>설명</th>
</tr>
</thead><tbody>
<tr>
<td>Trading Pair</td>
<td>거래 쌍. <a href="#ab37bf30de">거래쌍 목록 조회하기</a>에서 전체 목록을 확인할 수 있습니다.</td>
</tr>
<tr>
<td>Open</td>
<td>24시간 전의 가격</td>
</tr>
<tr>
<td>High</td>
<td>24시간 동안의 최고가</td>
</tr>
<tr>
<td>Low</td>
<td>24시간 동안의 최저가</td>
</tr>
<tr>
<td>Close</td>
<td>현재가 (1분마다 갱신)</td>
</tr>
<tr>
<td>Volume</td>
<td>24시간 동안의 거래량</td>
</tr>
<tr>
<td>Time</td>
<td>최근 데이터 갱신 시각</td>
</tr>
</tbody></table>

<aside class="notice">ISO 8601 타임스탬프를 이용하고 있습니다</aside>
<h1 id='errors'>Errors</h1><h3 id='http-status'>HTTP Status (응답 코드)</h3>
<table><thead>
<tr>
<th>오류 코드</th>
<th>설명</th>
</tr>
</thead><tbody>
<tr>
<td>400</td>
<td>잘못된 요청 - 요청 형식이 유효하지 않음</td>
</tr>
<tr>
<td>401</td>
<td>권한 없음 - 잘못된 API 키</td>
</tr>
<tr>
<td>403</td>
<td>금지됨 - 요청한 리소스에 대한 접근 권한이 없음</td>
</tr>
<tr>
<td>404</td>
<td>찾을 수 없음</td>
</tr>
<tr>
<td>429</td>
<td>요청 한도 초과 - API 호출 횟수 제한 초과</td>
</tr>
<tr>
<td>500</td>
<td>내부 서버 오류 - 서버에 문제가 발생함</td>
</tr>
</tbody></table>
<h3 id='gopax'>GOPAX 오류</h3>
<blockquote>
<p>오류 메시지 예제:</p>
</blockquote>
<pre class="highlight json tab-json"><code><span class="p">{</span><span class="w">
  </span><span class="s2">"errorCode"</span><span class="p">:</span><span class="w"> </span><span class="mi">201</span><span class="p">,</span><span class="w">
  </span><span class="s2">"errorMessage"</span><span class="p">:</span><span class="w"> </span><span class="s2">"Order server error: 201"</span><span class="w">
</span><span class="p">}</span><span class="w">
</span></code></pre>
<table><thead>
<tr>
<th>오류 코드</th>
<th>설명</th>
</tr>
</thead><tbody>
<tr>
<td>100, 106</td>
<td>자산 이름(Asset Name)이 올바르지 않음. <a href="#c8b9dcea10">자산 목록 조회하기</a>에서 전체 목록을 확인할 수 있습니다.</td>
</tr>
<tr>
<td>103</td>
<td>주문 종류(Type)가 올바르지 않음.</td>
</tr>
<tr>
<td>101, 104</td>
<td>거래 쌍(Trading Pair)이 올바르지 않음. <a href="#ab37bf30de">거래쌍 목록 조회하기</a>에서 전체 목록을 확인할 수 있습니다.</td>
</tr>
<tr>
<td>105</td>
<td>거래 쌍(Trading Pair)이 일시적으로 비활성화 되어있음. <a href="#ab37bf30de">거래쌍 목록 조회하기</a>에서 전체 목록을 확인할 수 있습니다.</td>
</tr>
<tr>
<td>107</td>
<td>주문 수량이 올바르지 않음.</td>
</tr>
<tr>
<td>108</td>
<td>주문 가격이 올바르지 않음.</td>
</tr>
<tr>
<td>201</td>
<td>주문을 위한 잔고가 부족.</td>
</tr>
<tr>
<td>202</td>
<td>주문 고유번호가 일치하지 않음.</td>
</tr>
<tr>
<td>203</td>
<td>주문 수량 X 주문 가격이 너무 큼.</td>
</tr>
<tr>
<td>204</td>
<td>현재 매수 주문이 허용되지 않음. 공지사항을 확인하십시오.</td>
</tr>
<tr>
<td>10153</td>
<td>API키가 올바르지 않음</td>
</tr>
</tbody></table>
<p><br />
<br />
<br />
<br />
<br /></p>

<p>© Streami, Inc. 모든 권리 보유.</p>

<p><br /></p>

      </div>
      <div class="dark-box">
          <div class="lang-selector">
                <a href="#" data-language-name="java">java</a>
                <a href="#" data-language-name="javascript">javascript</a>
                <a href="#" data-language-name="php">php</a>
                <a href="#" data-language-name="python">python</a>
                <a href="#" data-language-name="ruby">ruby</a>
          </div>
      </div>
    </div>
  </body>
</html>