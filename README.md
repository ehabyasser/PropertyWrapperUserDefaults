# PropertyWrapperUserDefaults


How to use it?

class UserManager{

    @UserDefault("isLoggedIn", defaultValue: false)
    static var isLoggedIn:Bool
    
    @CodableUserDefault("loggedUser", defaultValue: nil)
    static var user:User?
}
