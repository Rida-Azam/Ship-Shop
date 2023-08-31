# Ship-Shop
"Welcome to Ship Shop, where shopping meets convenience and excitement! 
Discover a world of possibilities as you explore our extensive range of products, 
from fashion to electronics and beyond. With top-tier security, user-friendly navigation, 
and a commitment to quality, we're here to redefine your online shopping experience.
Enjoy swift shipping, exclusive deals, 
and unparalleled customer support. Join our community of savvy shoppers and indulge in the art of shopping at your fingertips. 
Your satisfaction is our priority, and we can't wait to serve you on your journey through Ship Shop. Happy shopping!"

example
http://localhost:3200/api/all-orders

Brand:
router.get('/get-all-brand', getAllBrand)
router.get('/get-brand-by-id', getBrandbyId)
router.get('/get-brand-by-name', getBrandbyName)
router.post('/create-brand', createBrand)
router.put('/update-brand',updateBrand)
router.delete('/delete-brand',deleteBrand)

User:
router.get('/get-all-user', getAllUser)
router.get('/get-user-by-id', getUserbyId)
router.get('/get-user-by-email', getUserbyEmail)
router.post('/signup', Signup)
router.post('/login', LoginUser)
router.put('/update-user', updateUser)
router.delete('/delete-user', deleteUser)

Order:
router.get('/get-all-user', getAllUser)
router.get('/get-user-by-id', getUserbyId)
router.get('/get-user-by-email', getUserbyEmail)
router.post('/signup', Signup)
router.post('/login', LoginUser)
router.put('/update-user', updateUser)
router.delete('/delete-user', deleteUser)


Catergory:
router.get('/get-all-categories',getAllCategories)
router.get('/get-category-by-id',getCategorybyId)
router.get('/get-category-by-name',getCategorybyName)
router.post('/create-categories',createCategory)
router.put('/update-category',updateCategory)
router.delete('/delete-category',deleteCategory)




