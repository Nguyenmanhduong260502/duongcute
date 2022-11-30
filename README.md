# duongcute
zz
package quanlicanbo;

public class CanBo {

private String hoVaTen;
 private int namSinh;
 private String gioiTinh;
 private String diaChi;
 public CanBo() {}
 public CanBo(String hoVaTen, int namSinh, String gioiTinh, String diaChi) {
	
	this.hoVaTen = hoVaTen;
	this.namSinh = namSinh;
	this.gioiTinh = gioiTinh;
	this.diaChi = diaChi;
}
public String getHoVaTen() {
	return hoVaTen;
}
public void setHoVaTen(String hoVaTen) {
	this.hoVaTen = hoVaTen;
}
public int getNamSinh() {
	return namSinh;
}
public void setNamSinh(int namSinh) {
	this.namSinh = namSinh;
}
public String getGioiTinh() {
	return gioiTinh;
}
public void setGioiTinh(String gioiTinh) {
	this.gioiTinh = gioiTinh;
}
public String getDiaChi() {
	return diaChi;
}
public void setDiaChi(String diaChi) {
	this.diaChi = diaChi;
}
@Override
public String toString() {
	return "CanBo [hoVaTen=" + hoVaTen + ", namSinh=" + namSinh + ", gioiTinh=" + gioiTinh + ", diaChi=" + diaChi + "]";
}
}
