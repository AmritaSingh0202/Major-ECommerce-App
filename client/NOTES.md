created folder
npm create vite@latest
npm i
"npm run dev"
tailwind css install kiye
shadcn install ->add components;
react redux add kro->react-router dome ko then
in component auth-layout pages ke components bnao aur 
pages->auth->login.js ,register.js ke files
        admin-view-products, dashboard,orders, features {page bnao then routes create kro in App.jsx}
        shopping-view:home,list,checkout,account
        unauth-page bnao 

components:auth->layout.jsx
            admin-view->header,sidebar,layout->{Inke routes define in app.jsx}
            shopping-view:layout,header
            common:auth page.jsx
                   form.jsx-shadcn ke textarea label input add kre;

=Authentication/Authorization:
         1.if user not auth:then go to login
              if admin-admin dashboard pe jaye
              if user then shop home dash pe jaye
        2.if user authenticated then based on user role wo us page pe jayega like admin dash or shop home
        3.if auth hai but user is not admin and trying to access admin then go to unauth page:no data here
        4.If auth and admin is user trying to access shop page navigated to admin dash

=register and login page:common->form.jsx and config->index.jsx
