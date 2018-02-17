# User

describes user.

## attributes
  - User
    - user_id: UUID
    - screen_name: String
    - avatar_url: URI
    - email
    - is_private
    - password_hash

## ENDPOINTS

  - sign up     [POST]      `/user/sign_up`
  - sign in     [POST]      `/user/sign_in`
  - sign out    [POST]      `/user/sign_out`
  - update      [PATCH]     `/user`
  - DELETE      [DELETE]    `/user`

  - show        [GET]       `/users/:user_id`
