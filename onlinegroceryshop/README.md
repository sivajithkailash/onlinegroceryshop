# Online Grocery Shop

</p>

---
## FUNCTIONS
## Customer
- Customer need not to signup and login into system
- Just open website and browse the product that he/she wants to order
- Click on order and fill the address/contact details
- Customer can browse the product category wise

---

### Admin
- First admin will login ( for username/password run following command in cmd )
```
py manage.py createsuperuser
```
- Give username, email, password and your admin account will be created.
- After login , admin can view how many Prodct, Ctegory, order amount received on dashboard
- Admin can also view how many order received on dashboard
- Admin can view each order details with their customer location and contact number
- Admin can view/add/update/delete Product
- Admin can view/add/update/delete Category
- While adding category and product admin can provide second language and image.


---
### Other Features
- if category/product is deleted by admin then their respective order details will be deleted automatically

## HOW TO RUN THIS PROJECT
- Install Python(3.7.6) (Dont Forget to Tick Add to Path while installing Python)
- Open Terminal and Execute Following Commands :
```
python -m pip install -r requirements.txt

```
- Download This Project Zip Folder and Extract it
- Move to project folder in Terminal. Then run following Commands :
```
py manage.py makemigrations
py manage.py migrate
py manage.py runserver
```
- Now enter following URL in Your Browser Installed On Your Pc
```
http://127.0.0.1:8000/
```

## Disclaimer
This project is developed for demo purpose and it's not supposed to be used in real application.

## Feedback
Any suggestion and feedback is welcome. You can message me on facebook
- [Contact on Facebook](https://fb.com/sumit.luv)
- [Subscribe my Channel LazyCoder On Youtube](https://youtube.com/lazycoderonline)
