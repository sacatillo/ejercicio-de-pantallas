/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 */

package com.mycompany.ejercicio_de_pantallas;

/**
 *
 * @author Martin Montes
 */
import javax.swing.*;
import java.awt.*;
import java.awt.event.ActionEvent;
import java.awt.event.ActionListener;

public class ejercicio_panrallas{
    public static void main(String[] args) {
        // Crear el marco de la ventana
        JFrame frame = new JFrame("Formulario de Información del Usuario");
        frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
        frame.setSize(300, 200);
        frame.setLayout(new GridLayout(3, 2));

        // Crear etiquetas y campos de texto
        JLabel nameLabel = new JLabel("Nombre:");
        JTextField nameField = new JTextField();
        
        JLabel dobLabel = new JLabel("Fecha de Nacimiento (dd/mm/yyyy):");
        JTextField dobField = new JTextField();
        
        JButton submitButton = new JButton("Enviar");
        
        // Agregar componentes al marco
        frame.add(nameLabel);
        frame.add(nameField);
        frame.add(dobLabel);
        frame.add(dobField);
        frame.add(submitButton);
        
        // Acción al hacer clic en el botón
        submitButton.addActionListener(new ActionListener() {
            @Override
            public void actionPerformed(ActionEvent e) {
                String name = nameField.getText();
                String dob = dobField.getText();
                JOptionPane.showMessageDialog(frame, "Nombre: " + name + "\nFecha de Nacimiento: " + dob);
            }
        });

        // Hacer visible la ventana
        frame.setVisible(true);
    }
}