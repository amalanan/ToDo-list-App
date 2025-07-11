import 'package:flutter/material.dart';
import 'package:provider/provider.dart';
import 'package:todo_list_app_provider/models/save_task.dart';
import 'package:todo_list_app_provider/pages/add_todo.dart';
import 'package:todo_list_app_provider/pages/todo_list.dart';

void main() {
  runApp(
    ChangeNotifierProvider(
      create: (context) => SaveTask(),
      child: const MyApp(),
    ),
  );
}

class MyApp extends StatelessWidget {
  const MyApp({super.key});

  // This widget is the root of your application.
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      debugShowCheckedModeBanner: false,
      theme: ThemeData(brightness: Brightness.dark),
      initialRoute: '/',
      routes: {'/': (_) => TodoList(), '/add-todo-screen': (_) => AddTodo()},
    );
  }
}
