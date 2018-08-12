1.4 区块链查询服务
1.4.1 区块高度查询
接口地址：/block/height
请求方式：get
注：请求是需要在 header 里 Content-Type 需要设置 application/json
响应格式
成功：
{
    "success": true,
"data": [
{
        "peerAddress":"peer0.org1.example.com:7051",
            "height": 5,
"previousBlockHash":"IF98/odqfyJwX6hdduY="
            "currentBlockHash": "8v0a9h6t3FaNi2QVFYml0CK/3xtGPGa+8FAIziZhQME="
    }]
}
失败：
{
    "success": false,
    "msg": "区块高度查询失败，失败原因："
}
