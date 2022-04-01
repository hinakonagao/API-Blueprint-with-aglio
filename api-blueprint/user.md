# Group ユーザー

## 仮登録 [/api/preuser]

### 仮登録 [POST]

- Request

  - Body

    ```
    	{
    		"email": "test@email.com",
    		"email_confirmation": "test@email.com",
    		"password": "password",
    		"password_confirmation": "password"
    	}
    ```

- Response 201

  - Body

    ```
    	{
    		"user": {
    			"id": 4,
    			"email": "test@email.com"
    		}
    	}
    ```
