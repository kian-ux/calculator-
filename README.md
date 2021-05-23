# calculator-
It's intelligent calculator.it can calculate perimeter and area of triangle and square 
//  cal
print("hi, welcome to my intelligent calculator")
func creataccount(firstname: String, lastname: String, password: Double) {
func creataccount(firstname: String, lastname: String, password: Double) {
print("account seccessfully created")
}
let password = 1234
if password == 1234 {
creataccount(firstname:"kian", lastname:"akbari", password: 1234)
}
class triangle {
var base = 0.0
//
var height = 0.0
//
var firstside = 0.0
//
var secondside = 0.0
//
var area: Double {
    get {
return self.base * self.height / 2
   }
   set {
       print("Error ")
   }
}
var perimeter: Double {
    get {
return self.base + self.firstside + self.secondside
   }
   set {
       print("Error ")
   }
}
var pythagoras: Double {
    get {
return self.height * self.height + self.firstside * self.firstside
      }
   }
}
//cal
class calculat {
var a = 0.0
var b = 0.0
var c = 0.0
var d = 0.0
var e = 0.0
var f = 0.0
var g = 0.0
var h = 0.0
var i = 0.0
var j = 0.0
var k = 0.0
var l = 0.0
var toadd: Double {
    get {
return self.a + self.b + self.c + self.d + self.e + self.f + self.g + self.h + self.i + self.j + self.k + self.l
    }
    set {
        print("Error: invalid number")
    }
}
var subtraction: Double {
    get {
 return self.a - self.b - self.c - self.d - self.e - self.f - self.g - self.h - self.i - self.j - self.k - self.l
      }
      set {
          print("Error: invalid number")
      }
   }
var multiply: Double {
get {
    return self.a * self.b * self.c * self.d * self.e * self.f * self.g * self.h * self.i * self.j * self.k * self.l
  }
  set {
      print("Error: invalid number")
  }
}
  var divide: Double {
      get {
      return self.a / self.b / self.c / self.d / self.e / self.f / self.g / self.h / self.i / self.j / self.k / self.l
    }
    set {
     print("Error: invalid number")
    }
  }
}
class square {
    var side1: Double = 0
   var diameter: Double = 0
var area1: Double {
   return self.side1 * self.side1 
   }
   var area2: Double {
       return self.diameter * self.diameter / 2
   }
   var perimeter: Double {
    return self.side1 * 4
   }
}
var squ: square = square.init()
var plscalculat: calculat = calculat.init()
var m: triangle = triangle.init()
///////////////////////////objects
let sqcode = "" //👈👈👈👈👈👈
if sqcode == "perimeter" {
squ.side1 = 0.0 //👈
squ.diameter = 0.0 //👈
print(squ.perimeter)
}else if sqcode == "area1" {
    squ.side1 = 0.0 //👈
    squ.diameter = 0.0 //👈
    print(squ.area1)
}else if sqcode == "area2" {
squ.side1 = 0.0 //👈
squ.diameter = 0.0 //👈
print(squ.area2)
}else {
    print("Error: invalid number")
}
m.base = 0.0 //👈
m.height = 0.0 //👈
m.firstside = 0.0 //👈
m.secondside = 0.0 //👈
print(m.pythagoras) //👈
///::::::::::::cal
let doo = ""//👈👈👈👈👈👈
if doo == "toadd" {
plscalculat.a = 0.0 //👈
plscalculat.b = 0.0 //👈
plscalculat.c = 0.0
plscalculat.d = 0.0
plscalculat.e = 0.0
plscalculat.f = 0.0
plscalculat.g = 0.0
plscalculat.h = 0.0
plscalculat.i = 0.0
plscalculat.j = 0.0
plscalculat.k = 0.0
plscalculat.l = 0.0
print(plscalculat.toadd)
}else if doo == "multiply" {
plscalculat.a = 1.0 //👈
plscalculat.b = 1.0 //👈
plscalculat.c = 1.0
plscalculat.d = 1.0
plscalculat.e = 1.0
plscalculat.f = 1.0
plscalculat.g = 1.0
plscalculat.h = 1.0
plscalculat.i = 1.0
plscalculat.j = 1.0
plscalculat.k = 1.0
plscalculat.l = 1.0
print(plscalculat.multiply)
}else if doo == "subtraction" {
plscalculat.a = 0.0 //👈
plscalculat.b = 0.0 //👈
plscalculat.c = 0.0
plscalculat.d = 0.0
plscalculat.e = 0.0
plscalculat.f = 0.0
plscalculat.g = 0.0
plscalculat.h = 0.0
plscalculat.i = 0.0
plscalculat.j = 0.0
plscalculat.k = 0.0
plscalculat.l = 0.0
print(plscalculat.subtraction)
}else if doo == "divide" {
plscalculat.a = 0.0 //👈
plscalculat.b = 0.0 //👈
plscalculat.c = 0.0
plscalculat.d = 0.0
plscalculat.e = 0.0
plscalculat.f = 0.0
plscalculat.g = 0.0
plscalculat.h = 0.0
plscalculat.i = 0.0
plscalculat.j = 0.0
plscalculat.k = 0.0
plscalculat.l = 0.0
print(plscalculat.divide)
}else {
  print("Error: invalid number")
}
///::::::::::::
//
