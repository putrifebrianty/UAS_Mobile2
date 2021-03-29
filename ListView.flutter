import 'package:flutter/material.dart';

void main() {
  runApp(MaterialApp(
    debugShowCheckedModeBanner: false,
    title: 'Routing Navigation',
    initialRoute: '/',
    routes: {
      '/': (context) => MENU(),
      HalamanPertama.routeName: (context) => HalamanPertama(),
      HalamanKedua.routeName: (context) => HalamanKedua(),
      HalamanKetiga.routeName: (context) => HalamanKetiga(),
      HalamanKeempat.routeName: (context) => HalamanKeempat(),
      HalamanKelima.routeName: (context) => HalamanKelima(),
      HalamanKeenam.routeName: (context) => HalamanKeenam(),
    },
  ));
}

class MENU extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      backgroundColor : Colors.redAccent,
      appBar: AppBar(
        backgroundColor : Colors.redAccent,
        title: Text('Home'),
      ),
      body: Center(
        child: ListView(
          children: <Widget>[
            RaisedButton(
              child: Text('Profile'),
              color: Colors.deepPurpleAccent,
              onPressed: () {
                Navigator.pushNamed(context, HalamanPertama.routeName);
              },
            ),
            RaisedButton(
              child: Text('Search Job'),
              color: Colors.greenAccent,
              onPressed: () {
                Navigator.pushNamed(context, HalamanKedua.routeName);
              },
            ),
            RaisedButton(
              child: Text('Notification'),
              color: Colors.brown,
              onPressed: () {
                Navigator.pushNamed(context, HalamanKetiga.routeName);
              },
            ),
            RaisedButton(
              child: Text('Messages'),
              color: Colors.lightBlueAccent,
              onPressed: () {
                Navigator.pushNamed(context, HalamanKeempat.routeName);
              },
            ),
            RaisedButton(
              child: Text('Rate Card'),
              color: Colors.deepOrangeAccent,
              onPressed: () {
                Navigator.pushNamed(context, HalamanKelima.routeName);
              },
            ),
            RaisedButton(
              child: Text('Review'),
              color: Colors.lightGreenAccent,
              onPressed: () {
                Navigator.pushNamed(
                    context, HalamanKeenam.routeName);
              },
            ),
          ],
        ),
      ),
    );
  }
}

class HalamanPertama extends StatelessWidget {
  static const String routeName = "/halamanPertama";
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      backgroundColor : Colors.deepPurpleAccent,
      appBar: AppBar(
        backgroundColor : Colors.redAccent,
        title: Text("Profile"),
      ),
      body: Center(
        child: RaisedButton(
          child: Text('Back'),
           color: Colors.redAccent,
          onPressed: () {
            Navigator.pop(context);
          },
        ),
      ),
    );
  }
}

class HalamanKedua extends StatelessWidget {
  static const String routeName = "/halamanKedua";
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      backgroundColor : Colors.greenAccent,
      appBar: AppBar(
        backgroundColor : Colors.redAccent,
        title: Text("Search Job"),
      ),
      body: Center(
        child: RaisedButton(
          child: Text('Back'),
          color: Colors.redAccent,
          onPressed: () {
            Navigator.pop(context);
          },
        ),
      ),
    );
  }
}

class HalamanKetiga extends StatelessWidget {
  static const String routeName = "/halamanKetiga";
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      backgroundColor : Colors.brown,
      appBar: AppBar(
        backgroundColor : Colors.redAccent,
        title: Text("Notification"),
      ),
      body: Center(
        child: RaisedButton(
          child: Text('Back'),
          color: Colors.redAccent,
          onPressed: () {
            Navigator.pop(context);
          },
        ),
      ),
    );
  }
}

class HalamanKeempat extends StatelessWidget {
  static const String routeName = "/halamanKeempat";
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      backgroundColor : Colors.lightBlueAccent,
      appBar: AppBar(
        backgroundColor : Colors.redAccent,
        title: Text("Messages"),
      ),
      body: Center(
        child: RaisedButton(
          child: Text('Back'),
          color: Colors.redAccent,
          onPressed: () {
            Navigator.pop(context);
          },
        ),
      ),
    );
  }
}

class HalamanKelima extends StatelessWidget {
  static const String routeName = "/halamanKelima";
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      backgroundColor : Colors.deepOrangeAccent,
      appBar: AppBar(
        backgroundColor : Colors.redAccent,
        title: Text("Rate Card"),
      ),
      body: Center(
        child: RaisedButton(
          child: Text('Back'),
          color: Colors.redAccent,
          onPressed: () {
            Navigator.pop(context);
          },
        ),
      ),
    );
  }
}
class HalamanKeenam extends StatelessWidget {
  static const String routeName = "/halamanKeenam";
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      backgroundColor : Colors.lightGreenAccent,
      appBar: AppBar(
        backgroundColor : Colors.redAccent,
        title: Text("Review"),
      ),
      body: Center(
        child: Text('Review'),
      ),
    );
  }
}
