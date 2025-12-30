# docker-install-script
ubuntu မှာ docker install လုပ်တဲ့ command လေးတွေစုပြီး script လုပ်ထားတာပါ။ ဒီ script ကို run လိုက်တာနဲ့ docker install လုပ်ပြီးသား ဖြစ်မှာပါ

# How to run #
sudo chmod +x docker-install.sh  
./docker-install.sh

အားလုံးပြီးသွားပါက အောက်က command ကို ဆက် run ပေးပါ။ ပုံမှန်အတိုင်းဆိုရင် docker ကို sudo နဲ့ သုံးမှရပါတယ်။ Docker ကို ထည့်သွင်း ချိန် docker ဆိုတဲ့ linux user group တခုကို docker က create လုပ်သွားမှာဖြစ်ပါတယ်။ တကယ်လို့ မိမိက sudo ကို အမြဲ မထည့်ပေးစေချင်ဘူးဆိုရင် docker group ထဲကို လက်ရှိ user ကို add ပေးလိုက်ခြင်းဖြင့် sudo command ကို အမြဲရိုက်ထည့်ပေးစရာမလိုပဲ အသုံးပြုနိုင်ပါတယ်။

sudo usermod -aG docker ${USER}
