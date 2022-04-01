# Group ログイン

## ログイン [/login]

### ログイン [POST]

- Request

  - Body

    ```
    		{
    			"email": "test@example.com",
    			"password": "password"
    		}
    ```

- Response 200

  - Body

    ```
    		{
    			"user": {
    				"id": 2,
    				"email": "test@example.com"
    			}
    		}
    ```

## 管理者ログイン [/login/admin]

### 管理者ログイン [POST]

- Request

  - Body

    ```
    	{
    		"email":"admin@example.com",
    		"password":"11111111"
    	}
    ```

- Response 200

  - Body

    ```
    	{
    		"user": {
    			"id": 1,
    			"email": "admin@example.com",
    			"name": "システム管理者"
    		}
    	}
    ```
