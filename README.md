# ADSOIRE Business Dashboard - Vercel Deployment Guide

## 📦 Files Included
1. **adsoire_business_dashboard.html** - Main dashboard file (3,253 businesses embedded)
2. **package.json** - Project configuration
3. **vercel.json** - Vercel deployment settings

## 🚀 Quick Deploy to Vercel

### Option 1: Deploy via Vercel CLI (Recommended)

1. **Install Vercel CLI** (if not already installed):
```bash
npm install -g vercel
```

2. **Navigate to the folder** containing the dashboard files:
```bash
cd /path/to/your/dashboard/files
```

3. **Deploy with one command**:
```bash
vercel
```

4. **Follow the prompts**:
   - Login/signup to Vercel
   - Choose project name (e.g., "adsoire-dashboard")
   - Select default options
   - Your dashboard will be live in seconds!

### Option 2: Deploy via Vercel Dashboard

1. **Go to** [vercel.com](https://vercel.com)
2. **Sign up/Login** to your account
3. **Click "Add New Project"**
4. **Choose "Import Third-Party Git Repository"** OR drag and drop the folder
5. **Upload the folder** containing all three files
6. **Click "Deploy"**
7. **Your dashboard is live!**

### Option 3: Deploy via GitHub

1. **Create a new GitHub repository**
2. **Upload these files** to the repository:
   - adsoire_business_dashboard.html
   - package.json
   - vercel.json
3. **Connect GitHub to Vercel**:
   - Go to [vercel.com](https://vercel.com)
   - Click "Import Project"
   - Choose "Import Git Repository"
   - Select your repository
4. **Click "Deploy"**

## 🔗 Your Live URL

After deployment, you'll get a URL like:
- `https://adsoire-dashboard.vercel.app`
- `https://your-project-name.vercel.app`

You can share this link with anyone!

## 🎯 Dashboard Features

- **3,253 businesses** from Begumpet and Somajiguda areas
- **Multi-select filters** for locations and business types
- **453 unique localities** identified
- **21 business categories** organized
- **Real-time filtering** without page reload
- **Mobile responsive** design
- **Hover details** with Google Maps links
- **Digital gap analysis** (39.6% businesses without websites)

## 📊 Key Statistics
- Total Businesses: 3,253
- With Website: 1,966 (60.4%)
- Without Website: 1,287 (39.6%)
- Data Sources: Begumpet (1,553) + Somajiguda (1,700)

## 🔄 Updating Data

To update with new Excel files:

1. Process new Excel files to JSON format
2. Replace the data in the HTML file (look for `businessData = `)
3. Redeploy to Vercel (it auto-updates if using GitHub)

## 🛠️ Customization

You can customize:
- **Colors**: Search for `--primary-gradient` in the HTML
- **Company Name**: Replace "ADSOIRE DIGITAL VISIBILITY"
- **Filters**: Modify the filter logic in JavaScript section
- **Statistics**: Add/remove stat cards as needed

## 💡 Pro Tips

1. **Custom Domain**: You can add your own domain in Vercel settings
2. **Analytics**: Add Google Analytics by inserting the tracking code
3. **Password Protection**: Available in Vercel Pro plan
4. **Multiple Dashboards**: Deploy different versions for different areas

## 🆘 Troubleshooting

**Dashboard not loading?**
- Ensure all three files are in the same folder
- Check that HTML file size is under 100MB

**Filters not working?**
- Clear browser cache (Ctrl+F5)
- Try in incognito mode

**Can't deploy?**
- Make sure you have a Vercel account
- Check internet connection
- Try deploying via different method

## 📧 Support

For any issues or customization needs, contact ADSOIRE Digital Visibility.

---

**Ready to go live?** Your dashboard is production-ready and will work instantly on Vercel!
