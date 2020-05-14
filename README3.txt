package cn.itcast.filter;

import java.io.IOException;

import javax.servlet.Filter;
import javax.servlet.FilterChain;
import javax.servlet.FilterConfig;
import javax.servlet.ServletException;
import javax.servlet.ServletRequest;
import javax.servlet.ServletResponse;
import javax.servlet.http.HttpServletRequest;
import javax.servlet.http.HttpServletResponse;

import com.opensymphony.xwork2.ActionContext;
import com.opensymphony.xwork2.ActionSupport;

import cn.itcast.dao.IUserDAO;
import cn.itcast.dao.impl.UserDAO;
import cn.itcast.domain.User;
/**
 * 原理是，将所有的地址中包含JSP的访问拦截，将访问重定位到网站的跟目录
 * @author yu
 */
/*
public class URLFilter implements Filter{

    @Override
    public void destroy() {
        // TODO Auto-generated method stub
        
    }
    private String username;
    private String password;
    public String getUsername(){
        return username;
    }
    public void setUsername(String username){
        this.username=username;
    }
    public String getPassword() {
        return password;
    }
    public void setPassword(String password) {
        this.password = password;
    }
    @Override
    public void doFilter(ServletRequest request, ServletResponse response,
            FilterChain filterch) throws IOException, ServletException {
        // TODO Auto-generated method stub
        HttpServletRequest httpreq = (HttpServletRequest) request;
        StringBuffer url = httpreq.getRequestURL();
        IUserDAO userDAO=new UserDAO();
        User user=userDAO.validateUser(getUsername(),getPassword());
        ActionContext actionContext = ActionContext.getContext();
        //System.out.println("5");
        //System.out.println(user);
        //System.out.println(actionContext.getSession().get("user"));
        //System.out.println("5");
        if(url.indexOf("jsp") > 0 )   //判断地址中是否包含"JSP"
        {
            HttpServletResponse httpres = (HttpServletResponse) response;
            httpres.sendRedirect(httpreq.getContextPath());  //跳转到网站根目录，也可以根据自己的需要重定位到自己的Action
            return;
        }else{ //不包含JSP，则继续执行
            filterch.doFilter(request, response);   
        }
        
    }

    @Override
    public void init(FilterConfig arg0) throws ServletException {
        // TODO Auto-generated method stub
        
    }

}*/
