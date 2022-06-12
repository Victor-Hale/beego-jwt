# beego-jwt
本库在原有的dgrijalva开发的goland的jwt方法中，添加了表面封装


func RefreshToken：：刷新jwt token


func ValidateToken：：验证jtw token


func GenerateToken//获取jwt token


func GetHeaderTokenValue   return this result to client then all later request should have header "Authorization: Bearer <token> "
  
  
func MD5  //生成32位MD5
  
  
func HashAndSalt  //生成hash256加盐加密
  
  
func ComparePasswords// 验证hash256密码
  
