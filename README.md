using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace StockExchange
{
    class Controller
    {
        LogicalDataLayer LDL = new LogicalDataLayer();
        DAL DAL = new DAL();
        
        public String LoginCheck(String UserId, String PassWord)
        {
            return LDL.LoginCheck(UserId, PassWord);
        }

    }
}
