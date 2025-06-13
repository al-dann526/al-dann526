list.jsonAPI/Image/peta-screenshot.jsb6e24a7b1536dca9449ed2a13e2ebceb62e3a570axios.get('https://nirkyy-dev.hf.space/api/v1/game-islamic')
.then(response => {
  console.log('Status:', response.status);
  console.log('Headers:', response.headers);
  console.log('Data:', response.data);
})
.catch(error => {
  console.error('Error:', error.response ? error.response.data : error.message);
});{
  "published_By": "NirKyy",
  "success": true,
  "data": {
    "soal": "nama sahabat yang menemani nabi muhammad hijrah ke madinah?",
    "jawaban": "abu bakar",
    "hint": "ab× b××ar"
  }
}Status: 200 
access-control-allow-credentials: true
access-control-allow-headers: Content-Type, Authorization
access-control-allow-methods: GET, POST, PUT, DELETE, OPTIONS
access-control-allow-origin: *
content-length: 196
content-type: application/json; charset=utf-8
date: Fri, 13 Jun 2025 19:14:06 GMT
etag: W/"c4-iZhcC/kqtnvydYpU3Lxf4xNC4O0"
link: <https://huggingface.co/spaces/nirkyy/dev>;rel="canonical"
ratelimit-limit: 50
ratelimit-policy: 50;w=60
ratelimit-remaining: 44
ratelimit-reset: 18
vary: origin, access-control-request-method, access-control-request-headers
x-powered-by: Express
x-proxied-host: http://10.108.148.121
x-proxied-path: /api/v1/game-islamic
x-proxied-replica: ccyyrgf5-h7sfc
x-request-id: FW3Oiz
