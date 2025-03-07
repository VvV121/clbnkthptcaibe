<html>
<head>
<style>
.banner {
       background: url("img/img-0.jpg") no-repeat center center;
        background-size: cover;
        padding-top: 12rem;
        padding-bottom: 12rem;
        text-align: center !important;
        color: ivory !important;
}
.slogan {
         text-akign: center !important;
         width: 100%;
}
.row {
     display: flex;
     flex-wrap: wrap;
     max-width: 100%;
     background-color: lightgreen;
}
.block_3 {
     flex: 0 0 auto;
     width: 30%;
     margin: 10px;
}
.cell_img {
     width: 50%;
}
.cell_text {
     width: 50%;
     padding-left: 5rem;
}
.img {
     width: 100%;
     height: 100%;
}
.text-content {
       font-size: 36px;
       color: #333;
}
.footer {
   background-color: lightgrey;
   margin: 1px;
   padding: 10px;
}
.link {color:navy; text-align: left;}
.menu {font-size: 120%; text-decoration: none;}
.cell {text-align:justify; padding: 1.5cm;}
.table {padding: 10px; border: 2px solid bluel margin-left: 30%; margin-right: 30%; background-color: lightyellow;)
.td  {padding-top: 0.5em; padding-bottom: 0.5em;}
</style>
</head>
<body>
<table>
<form>
      <tr>
              <td colspan="2" align="center"><h3> ĐĂNG KÍ THÀNH VIÊN CLB NGOẠI KHÓA<br>TRƯỜNG THPT CÁI BÈ</h3></td>
      </tr>
      <tr>
              <td><label>Họ tên:</label></td>
              <td><input type="text" id="hoten" name="hoten"></td>
      </tr>
      <tr>
              <td><label>Email:</label></td>
              <td><input type="email" id="email" name="email"></td>
      </tr>
      <tr>
              <td><label>Ngày sinh:</label></td>
              <td><input type="date" id="ngaysinh" name="ngaysinh"></td>
      </tr>
      <tr>
              <td><label>Địa chỉ:</label></td>
              <td><textarea id="diachi" name="diachi" rows=5 cols=20></textarea></td>
      </tr>
      <tr>
              <td><label>Giới tính:</label></td>
              <td>
                     <input type="radio" id="nam" name="gioitinh"><label>Nam</label><br>
                     <input type="radio" id="nu" name="gioitinh"><label>Nữ</label><br>
              </td>
       </tr>
       <tr>
              <td><label>Sở thích:</label></td>
              <td>   
                     <input type="checkbox" id="covua" name="sothich"><label>Cờ vua</label><br>
                     <input type="checkbox" id="game" name="sothich"><label>Trò chơi điện tử</label><br>
                     <input type="checkbox" id="dulich" name="sothich"><label>Du lịch</label><br>
                     <input type="checkbox" id="camhoa" name="sothich"><label>Cắm hoa</label><br>
                     <input type="checkbox" id="nauan" name="sothich"><label>Nấu ăn</label><br>
              </td>
         </tr>
         <tr>
                <td><label>Hồ sơ đính kèm:</label></td>
                <td><input type="file" id="hoso" name="hoso" value="Lý lịch"></td>
         </tr>
         <tr>
                <td><label>Đăng kí CLB:</label</td>
                <td><select id="thethao" name="thethao">
                                 <option value="bongda">Bóng đá</option>
                                 <option value="bongban">Bóng bàn</option>
                                 <option value="bongro">Bóng rổ</option>
                                 <option value="bongchuyen">Bóng chuyền</option>
                                 <option value="caulong">Cầu lông</option>
                                 <option value="boiloi">Bơi lội</option>
                                 <option value="vothuat">Võ thuật</option>
                                 <option value="mithuat">Mĩ thuật</option>
                                 <option value="nhiepanh">Nhiếp ảnh</option>
                                 <option value="amnhac">Âm nhạc</option>
                                 <option value="khieuvu">Khiêu vũ</option>
                        </select>
                  </td>
            </tr>
            <tr>
                  <td colspan="2" align="center"><input type="submit" value="     Đăng kí      "></td>
            </tr>
</form>
</table>
</body>
</html>

