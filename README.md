# FANUC-PICTURE-mRuby-snippets
包含FANUC-PICTURE 8.0以后版本的mRuby的函数片段
## 代码片段
**脚本分段**

    if AGR[] == x then

**画面切换**

    :symbol: = "画面号"

    swscreen(0, 100 + :symbol(1):, :symbol(2):, 0, 99, 0)   
    
## FANUC PICTURE 函数

>   absolute(axis)

>   absolute2(axis)

>   absolute3(axis)

>   accdecdly(axis)

>   accdecdly3(axis)

>   acos(x)

>   actf

>   actf3

>   acts

>   acts2(spno)

>   adcnv(inptype,avtype)

>   alarm

>   asin(x)

>   atan(x)

>   atan2(x,y)

>   ceil(x)

>   chgtxtmsg(id,type)

>   copyval(k1,n1,t1,d1,p1,k2,n2,t2,d2,p2,pmc,add)

>   cos(x)

>   cosh(x)

>   deltool(number,datanum)

>   diagnoss(number,axis,length)

>   distance(axis)

>   distance3(axis)

>   errno

>   exp(x)

>   fabs(x)

>   fetchtool(number,datanum)

>   floor(x)

>   fmod(x,y)

>   script(sno(,arg0)(,arg1)(,arg2)(,arg3)(,arg4))

>   frexp_exponent(x)

>   frexp_mantissa(x)

>   GetDrvVersion

>   GetFPinfo(type,datatype)

>   getmacval(number)

>   getpath(type)

>   idprogdel(kind,datanum)

>   idprogsrch(kind,datanum)

>   idrdmac(kind,datanum)

>   idrdpmac2(kind,datanum)

>   idrdpmc(kind,datanum)

>   idrdpmcb(kind,datanum)

>   idrdset2(kind,datanum)

>   idrdtofs2(kind,datanum)

>   idwrmac(kind,datanum)

>   idwrpmac2(kind,datanum)

>   idwrpmc(kind,datanum)

>   idwrpmcb(kind,datanum)

>   idwrset(kind,datanum)

>   idwrtofs(kind,datanum)

>   isnan(x)

>   ldexp(x,exp)

>   loadtorq(motor,axis,coefficient,deccnt)

>   log(x)

>   log10(x)

>   machine(axis)

>   machine3(axis)

>   modf_decimal(x)

>   modf_integer(x)

>   movrlap(axis,unit,pmc,address)

>   movrlap3(axis,unit,pmc,address)

>   msghis(block,item,linkout)

>   pow(x,y)

>   progdel(number,pmc,address)

>   progsrch(number,pmc,address)

>   rd1length(grpnum,toolnum)

>   rd1radius(grpnum,toolnum)

>   rd2length(grpnum,tusenum)

>   rd2radius(grpnum,tusenum)

>   rdalminfo(type,almtype,num,pmc,address)

>   rdcount(number)

>   rdcursor(type,fix,kind2,address2,kind3,address3,pmc,address)

>   rdexecprog(block,pmc,address)

>   rdgrpid(number)

>   rdlife(number)

>   rdmacro(number,pmc,address)

>   rdmemsize(kind)

>   rdmodal(type,block,inp,pmc,address)

>   rdncstats(kind)

>   rdngrp

>   rdntool(number)

>   rdopmsg(type,pmc,address)

>   rdopmsg2(mode,type,pmc,address)

>   rdparam(number,axis,length)

>   rdpitchr(number)

>   rdpmacro(type,num)

>   rdpmc(adrtype,snumber,datatype)

>   rdpmcb(adrtype,snumber,bitpos)

>   rdpmcbr(adrtype,snumber,pos,len,data,type,adrtype2,snumber2,pmc,address)

>   rdpmcreal(adrtype,snumber,datatype)

>   rdprgdir(type,sprg,eprg,pmc,address)

>   rdprgdir2(type,num,pmc,address)

>   rdprgnum(type)

>   rdproginfo(type)

>   rdprojsetting(mainitem,subitem,kind,datanum,datasize,pmc,address)

>   rdseqnum

>   rdspload(spno)

>   rdstr(kind,snumber,first,count,pmc,address(,path)]

>   rdtofs(number,type)

>   rdtofs3(number,type)

>   rdtool(number,id)

>   rdzofs(number,axis)

>   rdzofs3(number,axis)

>   relative(axis)

>   relative2(axis)

>   relative3(axis)

>   remove_handler(sno,type,arg1,arg2,arg3)

>   scroll(id,type,arg1,arg2)

>   set_handler(sno,type,arg1,arg2,arg3)

>   setdecimal(dec)

>   seterrno(no)

>   setmacval(number,value)

>   setmaxlimit(max)

>   setminlimit(min)

>   setpath(path)

>   setproperty(type1,type2,arg1,arg2,arg3,arg4,arg5,arg6,arg7,arg8,arg9,arg10)

>   setrdprgtop(top)

>   settimer(type,area,address,pmc,address)

>   sin(x)

>   sinh(x)

>   skip(axis)

>   skip3(axis)

>   sleep(msec)

>   sqrt(x)

>   srvdelay(axis)

>   srvdelay3(axis)

>   statinfo(type)

>   swpath(systemtype,pathnumber)

>   swscreen(type,kind,datanum,default,pmc,address)

>   sysinfo(type)

>   t1info(grpnum,toolnum)

>   t2info(grpnum,tusenum)

>   tan(x)

>   tanh(x)

>   toolnum(grpnum,tusenum)

>   unfetchtool

>   wrcursor(type,fix,kind2,address2,kind3,address3,pmc,address(,size))

>   wrmacro(number,data1,data2,pmc,address)

>   wrparam(number,axis,length,data,pmc,address)

>   wrpmacro(num,data,decimal)

>   wrpmc(adrtype,snumber,datatype,data)

>   wrpmcb(adrtype,snumber,bitpos,data)

>   wrpmcbr(adrtype,snumber,pos,len,data,type,adrtype2,snumber2,pmc,address)

>   wrpmcreal(adrtype,snumber,datatype,data)

>   wrprojsetting(mainitem,subitem,kind,datanum,datasize,pmc,address)

>   wrstr(kind,snumber,first,count,data,pmc,address(,path))

>   wrtofs(number,type,data,pmc,address)

>   wrtool(number,id,data)

>   scriptasync(sno(,arg0)(,arg1)(,arg2)(,arg3)(,arg4))

>   set_handlerasync(sno,type,arg1,arg2,arg3)