# Open_Json-Url-using-Urllib ij Python 3.7
This code using Urllib to open a url which contains Json formated dats. Then using json read methode to read the data and itrate through the data to get the count s ath finally made 
the total of that sum by converig to integer.

Exampple URl - https://pt.wikipedia.org/wiki/Wikip%C3%A9dia:P%C3%A1gina_principal

Here we can have some information into the url
Protocol - https
Host - pt.wikipedia.org
Portnumber - defoult - http - 80, Https - 430
Path - wiki
Quarystring - Wikip%C3%A9dia:P%C3%A
Hash Tag - A1gina_principal

Urllib -  methods
['__builtins__', '__cached__', '__doc__', '__file__', '__loader__', '__name__', '__package__', '__path__', '__spec__', 'error', 'parse', 'request', 'response']

Urrlib.request

['AbstractBasicAuthHandler', 'AbstractDigestAuthHandler', 'AbstractHTTPHandler', 'BaseHandler', 'CacheFTPHandler', 'ContentTooShortError', 'DataHandler', 'FTPHandler', 'FancyURLopener', 'FileHandler', 'HTTPBasicAuthHandler', 'HTTPCookieProcessor', 'HTTPDefaultErrorHandler', 'HTTPDigestAuthHandler', 'HTTPError', 'HTTPErrorProcessor', 'HTTPHandler', 'HTTPPasswordMgr', 'HTTPPasswordMgrWithDefaultRealm', 'HTTPPasswordMgrWithPriorAuth', 'HTTPRedirectHandler', 'HTTPSHandler', 'MAXFTPCACHE', 'OpenerDirector', 'ProxyBasicAuthHandler', 'ProxyDigestAuthHandler', 'ProxyHandler', 'Request', 'URLError', 'URLopener', 'UnknownHandler', '__all__', '__builtins__', '__cached__', '__doc__', '__file__', '__loader__', '__name__', '__package__', '__spec__', '__version__', '_cut_port_re', '_ftperrors', '_have_ssl', '_localhost', '_noheaders', '_opener', '_parse_proxy', '_proxy_bypass_macosx_sysconf', '_randombytes', '_safe_gethostbyname', '_thishost', '_url_tempfiles', 'addclosehook', 'addinfourl', 'base64', 'bisect', 'build_opener', 'contextlib', 'email', 'ftpcache', 'ftperrors', 'ftpwrapper', 'getproxies', 'getproxies_environment', 'getproxies_registry', 'hashlib', 'http', 'install_opener', 'io', 'localhost', 'noheaders', 'os', 'parse_http_list', 'parse_keqv_list', 'pathname2url', 'posixpath', 'proxy_bypass', 'proxy_bypass_environment', 'proxy_bypass_registry', 'quote', 're', 'request_host', 'socket', 'splitattr', 'splithost', 'splitpasswd', 'splitport', 'splitquery', 'splittag', 'splittype', 'splituser', 'splitvalue', 'ssl', 'string', 'sys', 'tempfile', 'thishost', 'time', 'to_bytes', 'unquote', 'unquote_to_bytes', 'unwrap', 'url2pathname', 'urlcleanup', 'urljoin', 'urlopen', 'urlparse', 'urlretrieve', 'urlsplit', 'urlunparse', 'warnings']



Here  we using urllib.import.urlopen() open methode to open the URL
