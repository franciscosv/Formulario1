# Formulario1
     private void GuardarAlumno(object sender, EventArgs e)
        {
            grpGuardado.Visible = true;
            lbRut.Text = txtRut.Text;

            grpGuardado.Visible = true;
            lbNombre.Text = txtNombre.Text;

            grpGuardado.Visible = true;
            lbApellido.Text = txtApellido.Text;

            grpGuardado.Visible = true;
            lbDireccion.Text = TxtDireccion.Text;

            grpGuardado.Visible = true;
            lbTelefono.Text = txtTelefono.Text;

            grpGuardado.Visible = true;
            lbCiudad.Text = cbxCiudad.Text;
            


        }

        private void btnLimpiar_Click(object sender, EventArgs e)
        {
            grpGuardado.Visible = false;
            txtRut.Text = "";

            grpGuardado.Visible = false;
            txtNombre.Text = "";

            grpGuardado.Visible = false;
            txtApellido.Text = "";

            grpGuardado.Visible = false;
            TxtDireccion.Text = "";

            grpGuardado.Visible = false;
            txtTelefono.Text = "";

            grpGuardado.Visible = false;
            cbxCiudad.Text = "";
        }
    }
}
